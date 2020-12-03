<template>
  <div class="w-full h-16 bg-blue-600 p-3 flex">
    <img src="https://i.ibb.co/HGctH3T/mmlogo.png" class="h-10" />
    <a
      class="text-white px-4 py-2 ml-auto cursor-pointer hover:bg-white hover:bg-opacity-10 rounded"
      href="https://micromag.cc"
      >Main Website</a
    >
  </div>
  <div class="w-full bg-blue-500 text-center py-12">
    <div class="snow" />
    <h1 class="text-5xl font-bold font-sans text-white mb-6">
      Ultimate micro:bit Gift Guide
    </h1>
    <p class="text-lg text-gray-200 px-4">
      We've compiled a list of our favourite micro:bit products for any
      micro:bit maker this holiday season.
    </p>
  </div>
  <div class="m-6 mb-8">
    <h1 class="text-3xl font-bold font-sans mb-8">
      BBC micro:bit Essentials
    </h1>
    <div class="grid md:grid-cols-5 sm:grid-cols-1 gap-4">
      <Card
        name="micro:bit V2 (Single)"
        subtitle="£12.59 - OKdo"
        image="https://micromag.cc/content/images/size/w2000/2020/10/main.png"
        link="https://www.okdo.com/p/bbc-microbit/"
      />
      <Card
        name="micro:bit V2 Go (Starter Kit)"
        subtitle="£16.20 - OKdo"
        image="https://cdn.shopify.com/s/files/1/2962/4548/products/20201009_042220000_iOS_1024x1024@2x.jpg?v=1602383099"
        link="https://www.okdo.com/p/bbc-microbit-go-starter-kit/"
      />
      <Card
        name="Crocodile Leads"
        subtitle="£2.16 - OKdo"
        image="https://www.okdo.com/wp-content/uploads/2020/10/2048233-Main-Image.jpg?fit=800%2C800&resize=800,800"
        link="https://www.okdo.com/p/crocodile-leads-pack-of-10/"
      />
    </div>
  </div>
  <div class="m-6">
    <h1 class="text-3xl font-bold font-sans mb-8">
      Robots
    </h1>
    <div class="grid md:grid-cols-5 sm:grid-cols-1 gap-4">
      <Card
        name="4Tronix Mini:bit"
        subtitle="£24.96 - 4Tronix"
        image="https://cdn.shopify.com/s/files/1/0174/1800/products/IMG_3085a_1024x1024_88121ec4-74ab-4e70-a740-f1406aaaf63d_1024x1024.jpg?v=1567437798"
        link="https://shop.4tronix.co.uk/products/minibit"
      />
      <Card
        name="4Tronix Bit:Bot"
        subtitle="£42 - 4Tronix"
        image="https://cdn.shopify.com/s/files/1/0271/0223/products/IMG_3352a_1024x1024.jpg?v=1570703152"
        link="https://shop.4tronix.co.uk/products/bitbotxl?_pos=9&_sid=f379e9d5d&_ss=r"
      />
      <Card
        name="Kitronik :MOVE mini MK2"
        subtitle="£27.54 - Kitronik"
        image="https://cdn.shopify.com/s/files/1/2311/3697/products/move-mini-mk2-buggy-kit-excluding-microbit-bbc-micro-bit-robotics-other-kitronik-cool-components-991_705x700.jpg?v=1601039053"
        link="https://kitronik.co.uk/products/5652-move-mini-mk2-buggy-kit-excl-microbit?_pos=8&_sid=b95c59248&_ss=r"
      />
      <Card
        name="Dexter GiggleBot"
        subtitle="£59.99 - Pi Hut"
        image="https://cdn.shopify.com/s/files/1/0176/3274/products/MMP-1414-7_500x.jpg?v=1561292875"
        link="https://thepihut.com/products/dexter-gigglebot-base-kit"
      />
      <Card
        name="Kitronik  Simple Robotics"
        subtitle="£29.94 - Kitronik"
        image="https://cdn.shopify.com/s/files/1/0254/1191/1743/products/5665_large-simple-robotics-kit-microbit-klip-tt-motor-robot-build1_3165767d-4183-41af-9359-800698d301fd_800x.jpg?v=1582132435"
        link="https://kitronik.co.uk/products/5665-simple-robotics-kit-single-pack"
      />
    </div>
  </div>
  <div class="m-6">
    <h1 class="text-3xl font-bold font-sans mb-8">
      RGB LED add-ons
    </h1>
    <div class="grid md:grid-cols-5 sm:grid-cols-1 gap-4">
      <Card
        name="SnowPi RGB"
        subtitle="£9.00 - SnowPi Store"
        image="https://cdn.shopify.com/s/files/1/0446/2143/0938/products/classic_1000x1500.jpg?v=1596114773"
        link="https://snowpi.xyz/buy/"
      />
      <Card
        name="Kitronik :ZIP Halo HD"
        subtitle="£25.80 - Kitronik"
        image="https://www.lextronic.fr/36714-thickbox_default/zip-halo-hd-pour-microbit.jpg"
        link="https://kitronik.co.uk/products/5672-kitronik-zip-halo-hd-for-microbit?_pos=1&_sid=8a4b3a427&_ss=r"
      />
      <Card
        name="4Tronix Cube:Bit"
        subtitle="£21.60/£90 - 4Tronix"
        image="https://cdn.shopify.com/s/files/1/0271/0223/products/IMG_2280a_1024x1024.jpg?v=1531727723"
        link="https://shop.4tronix.co.uk/products/cubebit?variant=12698900955251"
      />
      <Card
        name="ProtoPic micro:pixel"
        subtitle="£17.78 - Pi Hut"
        image="https://proto-pic.co.uk/wp-content/uploads/2019/09/colour.jpg"
        link="https://proto-pic.co.uk/product/micropixel-4x8-ws2812b-board-for-bbc-microbit/"
      />
    </div>
  </div>
  <div class="m-6">
    <h1 class="text-3xl font-bold font-sans mb-8">
      Sound/Music add-ons (Great for V1)
    </h1>
    <div class="grid md:grid-cols-5 sm:grid-cols-1 gap-4">
      <Card
        name="MINI.MU Glove Kit"
        subtitle="£30 - Pimoroni"
        image="https://cdn.shopify.com/s/files/1/0174/1800/products/minimuglove_5f2ec02c-d3ae-4d14-a6ae-2fb3ff9225b5_1024x1024.jpg?v=1544803538"
        link="https://shop.pimoroni.com/products/mini-mu-glove-kit?variant=21240542560339"
      />
      <Card
        name="Pimoroni noise:bit"
        subtitle="£13.50 - Pimoroni"
        image="https://cdn.shopify.com/s/files/1/0174/1800/products/noise-bit-2_1024x1024.jpg?v=1531739795"
        link="https://shop.pimoroni.com/products/noise-bit"
      />
      <Card
        name="Kitronik MI:Sound"
        subtitle="£6 - Kitronik"
        image="https://cdn.shopify.com/s/files/1/0174/1800/products/5649_additional-mi-sound-speaker-microbit-cr2032-front_1024x1024.jpg?v=1568805881"
        link="https://kitronik.co.uk/products/5649-misound-speaker-board-for-bbc-microbit"
      />
    </div>
  </div>
  <div class="m-6">
    <h1 class="text-3xl font-bold font-sans mb-8">
      Electronics Kits
    </h1>
    <div class="grid md:grid-cols-5 sm:grid-cols-1 gap-4">
      <Card
        name="Kitronik Inventors Kit"
        subtitle="£24.95 - Kitronik"
        image="https://cdn-shop.adafruit.com/1200x900/4670-02.jpg"
        link="https://kitronik.co.uk/products/inventors-kit-for-the-bbc-micro-bit?_pos=3&_sid=78ec062b7&_ss=r"
      />
      <Card
        name="Monk Makes Electronics Starter"
        subtitle="£30 - Pi Hut"
        image="https://cdn.shopify.com/s/files/1/0176/3274/products/in_box_ready-copy-1024x881_500x.jpg?v=1550679269"
        link="https://thepihut.com/products/electronics-starter-kit-for-micro-bit"
      />
      <Card
        name="Kitronik Discovery Kit"
        subtitle="£11.94 - CPC"
        image="https://cpc.farnell.com/productimages/standard/en_GB/ED00486-40.jpg"
        link="https://cpc.farnell.com/kitronik/5666/discovery-kit-for-micro-bit/dp/ED00486"
      />
      <Card
        name="4Tronix Playground"
        subtitle="£48 - 4Tronix"
        image="https://cdn.shopify.com/s/files/1/0271/0223/products/IMG_2717a_1024x1024.jpg?v=1550320231"
        link="https://shop.4tronix.co.uk/products/playground-for-microbit-super-kit?_pos=3&_sid=ee3b99e68&_ss=r"
      />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Card from "@/components/card.vue";

export default defineComponent({
  name: "Home",
  components: {
    Card
  }
});
</script>

<style>
.snow:before {
  content: "";
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfQAAAH0CAMAAAD8CC+4AAAAflBMVEX///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////+yfIzaAAAAKnRSTlMAAgkMDQ4PERITFRlISVFUWVpgYmVobW5vc3Z3eXx9goSKjpWXoaOqrLIxv86ZAAACaElEQVR4Ae3dbW7iBhRA0WdcHJqCwRRDCsWvTT8m3v8GR7ADpPkx1jtnH1c3AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAYLHa9dQ3sVhvv359NPEScjrkORZr/vpz/idewuqamaexj2X65b95nv/+/IgX0O3zKZbp/Y/5KXjBlA9DF8v0NT/c34MX7C7HzLy1sUynf/+a5/n/t+AlYw73bGKpPuf7t7kJXrLNTRvL9fv821v8MAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA0K6nvgkqyemQ56CS1TUzT2Mf1NHt8ymoY8qHoQvq2F2OmXlrg0rGHO7ZBJVsc9MGAAAAAAAAAAAAFWIcxDiIcRDjIMZBjIMYBzEOAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQLue+iaoJKdDnoNKVtfMPI19UEe3z6egjikfhi6oY3c5ZuatjUoYc7hnE5WwzU0bAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIB/LP6x+Mf+xPxj8Y/FPxb/WPxjAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABo11PfRCXkdMhzVMLqmpmnsY866Pb5FHUw5cPQRR3sLsfMvLVRCWMO92yiEra5aWOxAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAoF1PfROVkNMhz1EJq2tmnsY+6qDb51PUwZQPQxd1sLscM/PWRiWMOdyziUrY5qaNWgAAAAAAAAAAAABAmIkwE2EmwkyEmQgzEWYizAQAAAAAAAAAAAAAgO+81Sm+KMVvegAAAABJRU5ErkJggg==),
    url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAZAAAAGQCAMAAAC3Ycb+AAABYlBMVEX////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////5zPnRAAAAdnRSTlMAAQIDBAUGBwgJCgsMDQ4PEBESExQVFhcYGRobHB0eHyAhIiMkJSYnKCorLC0uLzAxMjM0NTY3ODo7PD0+P0BBQkNERUZISktMTU5PUFFSU1VXWFlaW11eX2BhYmVnaGlqa21vcHJzdHV2d3l7fX5/gIGCg4WHZfG2JAAAB8BJREFUeAHt3X9XVNfZxvH7uvc+P2bmMDAM4DAZgmBAMQ+YRwSilWrRhBgpDZLGJNpKDbGNJjZJ7fuvdUz+yWoSLHj2Wv1+XgL3mn04++x9XSa5xxhchiS4Z2WrVUa3JMCLsf7c7KkqkyEFWXtu/cb1lemGy1A7Wdm7dOfwYPvcWJQMdXNrDDYPnj3dX+myZiVAbmVv4+7jw52lsTQGwkCyzuLm7e21mVaQ1Q6y0OjOnl3ot/mBJEIhb422m5nLkgB5iNGZRzr0nMlSBQAAAAAAAAAAAAAAAAAAAAAAAEAmN1kaoDSuycmG4AlcJJVckuE5hXJ41Tp3q4s8K4o8SmZQ/kMYQVRtv9HG2NSp8VbmZvDG9Mbdrw53ljqZrBbycuKti2vn+1UQ85A3B1cfDANtXFYHxZEz1z7+9IPlicIN3uit7n8xjHyyWigb/7+Pnvz9/pU3GjLoRSja71amG0FWB/mLgXz774G44WVs4FQV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),
    url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASwAAAEsCAMAAABOo35HAAABGlBMVEX///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////9y/ChlAAAAXnRSTlMAAQIDBAUGBwgJCgsMDQ4PEBESExQVFhcYGRobHB0eHyAhIiMkJSYoKSorLC8wMjM0NTY4OTo8PT4/QEFDSEpLTlBRUlNWV1pcXWBhYmdpa2xtb3B1dnd7fH6Bg4SFICRGzgAABJlJREFUeAHt3f9SE1kWwPF7zr23u5PODwiJEBI0IqAgQaMuS4Sgu2jvanQGxUEcZt7/Naacqpl/pmY8UFaaVH0/j/DlNEl3qs91zomqOFjdkFYAAIj64EUcDDRb7DRTJYSBpquPx7udyGgZaH04PS+2cmIZ+Obo9HK6QywLrW5MisPbKbEMJDT6693cE8tCfJolSisb+cr9PQAAAIg42IiPiSeX9SZvpdfiKZ6J1jaPjvfagdmyDNbSvz9enNxNiWUQlvY/fj4ZZMQy8FyGdhLq/IM3E43xhs8VAEBURRwsNFZrlaCEMJDYurczaPIIwULz+/99NxlUiGXgm08+/Ppup8Z1aKC1h//78J97FWIZSHLr4ZP7Le5dTDSpNXM+DY1E5//FFgAAAAAAAAAAAAAA1AcvDgYSqq12I6GWhVYHz8Y7C8yWgYTWsx8+vbSs7oGEzsGnn1/fzQyxoPXtl6//tRwNsSBx4fbd5Yo6A0hI02hsBREVBwAAgHldRAUNSVRTLkja6q3Ug6EWJLT3jo82a94ZMFiDk4uP++3gTIj1+WqxuAyVFAZ6hX/wkBD/+tUBAAAAnFao4gygSbOzkHlDLUjs7I4fr6aGWJB8qzifDuvq8E1a2377y+moaXhyCcn6h8Vko2qYLIjPV9f7DdPzJYgmWeqNrWA+rRAAAACiXp0FxKf1RtV0BwPNesPRRsNwDwMJi6Pp6aSfWGIRqzM+vyzWM0MsaHO3mB52oyEWNO1sba/laogF0VjNrT/YQJSxmoe3IiAak2DKBQ31Lqe3fv9zgfk9ISztn12cDFK5+b9U5XmiUm6s9v7Z5zmIpZXugwfdinAZGoT20zdvnpb8qovMyT/42H/x5cuLfnSlEh8Tf+NbSVw+eP/+wLRRiC+lmt959OhObvmrQnyl0ahwU2wjol7+sRW4iQUAAAAAAAAAAAAAURGZx51RKm7WQlarzt0+U4m1paVaEDdbmq9tb3VSKfVVAnFXpPXN/f3Nus76T9Q9nBbD0vYJib/OYEtcOTo7O1qJ4mZJsvXi8qfnnSDltLreYEvsHV9cHPdmHSvpT36cjha9K0dcvdZg+9beq1d7rTDjWL6xMRr2MnWlkOxecXk+7gR3NZK2B4N2KrM/JLdZT1VKipWsTU6vM9gasyxoGZ9GZaX6Y7BXM+Uww+892BBvTwVSAQAAAAAAAAAAAAAAAAAAAAAAAAAAAODF5ptD1FtXE4FlDHb2/TUcJCtJ//cFMmHOUmmSJd5eq7ydW+UTzbvr/UZws9/m9ta+9OqGkGzteTHZqEpZ69Tmida2316ejppeSlrUN0+kulWcT4d1LeNjRdx8kdjZHT9eTS2xoEmzs5ipONiW5npzK5RQCgAAAOD7NURjYjzwBD5f7rcrnhAGUrlz8OJpN2G0DLTx6P2XNw9yQyz4r7H+f/97x+IyhM9v9dsVdQYQjZGnvmbyZykAAAAAAAAAAAAAAAAAAES9OguIpvVG1bRoBpr1hqONhjfUQlgYTU8n/eSbsSAutsfnl8V6RixDLN/YLaaH3WiIBUk6W9truRpiQTRWq6k3tMJvuLRZnVwJllwAAAAASUVORK5CYII=);
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  z-index: 1;
  height: 18rem;
  -webkit-animation: snow 10s linear infinite;
  -moz-animation: snow 10s linear infinite;
  -ms-animation: snow 10s linear infinite;
  animation: snow 10s linear infinite;
}

@keyframes snow {
  0% {
    background-position: 0 0, 0 0, 0 0;
  }
  50% {
    background-position: 500px 500px, 100px 200px, -100px 150px;
  }
  100% {
    background-position: 500px 1000px, 200px 400px, -100px 300px;
  }
}
@-moz-keyframes snow {
  0% {
    background-position: 0 0, 0 0, 0 0;
  }
  50% {
    background-position: 500px 500px, 100px 200px, -100px 150px;
  }
  100% {
    background-position: 400px 1000px, 200px 400px, 100px 300px;
  }
}
@-webkit-keyframes snow {
  0% {
    background-position: 0 0, 0 0, 0 0;
  }
  50% {
    background-position: 500px 500px, 100px 200px, -100px 150px;
  }
  100% {
    background-position: 500px 1000px, 200px 400px, -100px 300px;
  }
}
@-ms-keyframes snow {
  0% {
    background-position: 0 0, 0 0, 0 0;
  }
  50% {
    background-position: 500px 500px, 100px 200px, -100px 150px;
  }
  100% {
    background-position: 500px 1000px, 200px 400px, -100px 300px;
  }
}
</style>
