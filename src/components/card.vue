<template>
  <div class="bg-white shadow-xl border border-gray-300 rounded-lg">
    <div
      class="w-full h-48 bg-cover bg-center bg-no-repeat rounded"
      :style="'background-image: url(' + image + ')'"
    />
    <div class="p-4 pt-6">
      <h1 class="font-bold text-2xl">{{ name }}</h1>
      <h1 class="text-xl">{{ subtitle }}</h1>
      <a :href="link">
        <button
          class="mt-4 py-2 px-4 rounded bg-blue-500 w-full font-bold text-white hover:opacity-75"
        >
          Buy Now
        </button>
      </a>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Card",
  props: {
    name: String,
    subtitle: String,
    image: String,
    link: String
  }
});
</script>
