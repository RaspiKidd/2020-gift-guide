<template>
  <div class="w-full h-16 bg-primary-alt p-3 flex">
    <img src="logo.png" class="h-10" />
    <a
      class="text-white px-4 py-2 ml-auto cursor-pointer hover:bg-white hover:bg-opacity-10 rounded"
      href="https://edublocks.org"
      >Main Website</a
    >
  </div>
  <div class="w-full h-32 bg-primary text-center">
    <h1 class="text-5xl font-bold font-sans text-white py-9">
      Projects Gallery (BETA)
    </h1>
  </div>
  <div class="m-6 ">
    <div class="flex mb-8">
      <h1 class="font-bold mt-3 mr-4">Sort projects by platform:</h1>
      <select
        class="block w-64 bg-grey-lighter border border-grey-lighter text-grey-darker py-3 px-4 pr-8 rounded"
        v-model="currentSelected"
      >
        <option>All</option>
        <option>Python</option>
        <option>microbit</option>
        <option>RPi</option>
        <option>CircuitPython</option>
      </select>
    </div>
    <div v-if="outputList.length < 1" class="text-center">
      <h1 class="text-4xl font-bold">No Projects Found 🙁</h1>
    </div>
    <div class="grid md:grid-cols-3 sm:grid-cols-1 gap-4">
      <div
        v-for="item in outputList"
        :key="item.id"
        class="p-4 bg-white shadow-xl border border-gray-300 rounded-lg transform hover:scale-102"
      >
        <a :href="item.url">
          <h1 class="text-xl font-bold">{{ item.name }}</h1>
          <div class="flex mt-2">
            <img :src="item.platform + '.png'" class="h-6 mr-3" />
            <h1 class="text-gray-600">{{ item.platform }}</h1>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent, ref, watchEffect } from "vue";
import firebase from "firebase";

export default defineComponent({
  name: "Home",
  setup() {
    const db = firebase.firestore();
    const itemList: any = ref([]);
    const outputList: any = ref([]);
    const itemListLength = ref();
    const currentSelected = ref("All");

    function filterByValue(array: any, string: string) {
      return array.filter((o: any) =>
        Object.keys(o).some(k =>
          o[k].toLowerCase().includes(string.toLowerCase())
        )
      );
    }

    watchEffect(() => {
      if (currentSelected.value === "All") {
        outputList.value = filterByValue(itemList.value, "");
      } else {
        outputList.value = filterByValue(itemList.value, currentSelected.value);
      }
    });

    db.collection("shared").onSnapshot(snapshot => {
      itemList.value = [];
      snapshot.forEach(doc => {
        itemList.value.push({
          id: doc.id,
          name: doc.data().name,
          url: doc.data().url,
          platform: doc.data().platform
        });
      });
      itemListLength.value = itemList.value.length;
      outputList.value = filterByValue(itemList.value, "");
    });
    return { outputList, currentSelected };
  }
});
</script>
