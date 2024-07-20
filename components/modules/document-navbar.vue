<!-- navbar -->

<template>
  <div class="grid w-full bg-neutral-200 py-2 px-4 relative">
    <div class="grid grid-cols-3 gap-2 items-center">
      <router-link to="/" class="text-neutral-700 text-2xl font-light">
        {{ $root.info.name }}
      </router-link>
      <div class="flex items-center justify-center gap-2">
        <router-link to="/page-2" class="text-neutral-600 flex gap-2 items-center font-light text-sm uppercase">
          <div class="ph-fill ph-egg"></div>
          Page 2
        </router-link>
      </div>
    </div>
  </div>
</template>
<style>
::selection {
  background-color: #020406;
  color: #fff;
}

::-moz-selection {
  background-color: #020406;
  color: #fff;
}

::-webkit-selection {
  background-color: #020406;
  color: #fff;
}

.slide-fade-enter-active,
.slide-fade-leave-active {
  transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
}

.slide-fade-enter,
.slide-fade-leave-to {
  height: 0;
  opacity: 0;
}
</style>

<script>
export default {
  data() {
    return {};
  },
};
</script>
