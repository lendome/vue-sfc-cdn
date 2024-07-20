<!-- home.vue -->

<template>
  <div class="flex items-center gap-6 flex-col justify-center h-full">
    <h1 class="text-7xl text-neutral-600 font-light">Second Page</h1>
    <p class="text-neutral-500 max-w-md text-center text-sm">
      Its set up with modal and routing support, and has the
      <span class="bg-neutral-500 text-neutral-200 px-1 rounded">Phosphorous</span>
      icon set and
      <span class="bg-neutral-500 text-neutral-200 px-1 rounded">Axios</span>
      imported using the CDN. <br /><br />Below you can see a list of imported
      CDNs, and whether they will break the framework upon removal.
    </p>
    <div class="grid rounded-lg overflow-hidden">
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">vue</div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-rose-100 text-rose-500 text-center rounded-full text-xs py-1 px-2">
            Needed
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">vue-router</div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-rose-100 text-rose-500 text-center rounded-full text-xs py-1 px-2">
            Needed
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">
          vue3-sfc-loader
        </div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-rose-100 text-rose-500 text-center rounded-full text-xs py-1 px-2">
            Needed
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">Axios</div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-amber-100 text-amber-500 text-center rounded-full text-xs py-1 px-2">
            Recommended
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">Phosphorous</div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-emerald-100 text-emerald-500 text-center rounded-full text-xs py-1 px-2">
            Not needed
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">Jquery</div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-emerald-100 text-emerald-500 text-center rounded-full text-xs py-1 px-2">
            Not needed
          </div>
        </div>
      </div>
      <div class="bg-neutral-400 items-center flex px-4 py-2">
        <div class="w-32 text-neutral-100 text-sm font-normal">
          Tailwind (Play CDN)
        </div>
        <div class="w-32 text-neutral-100 font-normal">
          <div class="bg-emerald-100 text-emerald-500 text-center rounded-full text-xs py-1 px-2">
            Not needed
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Your component logic goes here if needed. :3
  name: "Home",
  data() {
    return {};
  },
  methods: {},
  mounted() {},
};
</script>
