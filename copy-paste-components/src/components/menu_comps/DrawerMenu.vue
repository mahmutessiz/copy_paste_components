<script setup>
/**
 * ! Close the drawer
 */

function deneme() {
  const drawerChild = document.querySelector('#drawer-open-close');
  drawerChild.classList.add('hidden');
}
</script>

<template>
  <div
    class="fixed z-20 -mt-4 hidden h-screen w-full bg-white/50 pt-4 backdrop-blur-lg"
    @click="deneme"
  >
    <ul class="flex w-full flex-wrap">
      <li
        class="w-full cursor-pointer border border-b border-black/20 bg-gray-100/40 py-3 text-center text-xl transition-all duration-200 hover:bg-rose-500"
        @click="deneme"
      >
        <a href="/"><p class="w-full">Anasayfa</p></a>
      </li>

      <li
        class="w-full cursor-pointer border border-b border-black/20 bg-gray-200/40 py-3 text-center text-xl transition-all duration-200 hover:bg-rose-300"
        @click="deneme"
      >
        <p class="w-full">Ürünler</p>
      </li>
      <li
        class="w-full cursor-pointer border border-b border-black/20 bg-gray-100/40 py-3 text-center text-xl transition-all duration-200 hover:bg-rose-500"
        @click="deneme"
      >
        <a href="/"><p class="w-full">Hakkımızda</p></a>
      </li>
      <li
        class="w-full cursor-pointer border border-b border-black/20 bg-gray-200/40 py-3 text-center text-xl transition-all duration-200 hover:bg-rose-300"
        @click="deneme"
      >
        <a href="/"><p class="w-full">İletişim</p></a>
      </li>
    </ul>
  </div>
</template>
