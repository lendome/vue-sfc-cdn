<template>
  <div
    class="bg-stone-200 overflow-hidden gap-4 relative p-4 h-screen flex flex-col w-screen sm:h-auto sm:w-auto sm:rounded-lg"
  >
    <h1
      class="text-xl py-1 px-2 bg-stone-500 text-stone-100 rounded-md font-light uppercase"
    >
      Modal
    </h1>
    <p class="text-stone-500 max-w-sm p-2 text-sm">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae unde quae
      optio at minus, vel expedita ab sunt, quibusdam nulla inventore itaque
      officiis. Velit.
    </p>
    <div class="flex justify-end gap-2 items-center">
      <button
        @click="$root.activeModal = null"
        class="flex gap-2 items-center text-rose-400 font-normal text-sm transition-all duration-300 hover:gap-3 hover:text-rose-500 px-4 py-1"
      >
        <i class="ph-fill text-lg ph-prohibit"></i>

        Cancel
      </button>
      <button
        @click="$root.activeModal = null"
        class="bg-stone-500 flex gap-2 items-center text-stone-200 font-normal text-sm rounded-full transition-all duration-300 hover:bg-stone-500/75 hover:gap-3 hover:text-stone-100 px-4 py-1"
      >
        <i class="ph-fill text-lg ph-egg-crack"></i>

        Roger that!
      </button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {},
};
</script>
