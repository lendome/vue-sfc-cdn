<!-- home.vue -->

<template>
  <div class="flex items-center gap-4 flex-col justify-center h-full">
    <button @click="$root.activeModal = 'example-modal'"
      class="bg-neutral-500 flex gap-2 items-center text-neutral-200 font-normal text-sm rounded-full transition-all duration-300 hover:bg-neutral-400 hover:gap-3 hover:text-neutral-100 px-4 py-1">
      <i class="ph-fill text-lg ph-app-window"></i>

      test Modal
    </button>
    <h1 class="text-7xl text-neutral-600 font-light">Home</h1>
    <p class="text-neutral-500 max-w-md text-center text-sm">
      This is sorta a small template I made to quickly create vue CDN SPA apps
      that support
      <span class="bg-neutral-500 text-neutral-200 px-1 rounded">.vue</span> files.
      It uses the
      <a class="text-neutral-800" target="_blank"
        href="https://github.com/FranckFreiburger/vue3-sfc-loader">vue3-sfc-loader</a>
      by FranckFreiburger, heavy props to him.
    </p>
    <div class="grid gap-2">
      <div class="bg-neutral-400 rounded-lg px-2 py-1 text-center font-bold text-neutral-300 text-xl">
        <i class="ph-fill ph-cards"></i>
      </div>
      <div class="bg-neutral-400 grid gap-1 rounded-lg px-4 py-2 text-center font-bold text-neutral-300 text-xl">
        <div class="bg-neutral-300 h-2 w-24 rounded-full"></div>
        <div class="bg-neutral-300 mt-2 h-2 w-44 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-40 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-48 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-32 rounded-full"></div>
      </div>
      <div class="bg-neutral-400 grid gap-1 rounded-lg px-4 py-2 text-center font-bold text-neutral-300 text-xl">
        <div class="bg-neutral-300 h-2 w-24 rounded-full"></div>
        <div class="bg-neutral-300 mt-2 h-2 w-44 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-40 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-48 rounded-full"></div>
        <div class="bg-neutral-300 h-2 w-32 rounded-full"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Your component logic goes here if needed. :3
  name: "Home",
};
</script>
