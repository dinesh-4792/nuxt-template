<template>
  <div
    class="w-full py-2 px-4 bg-gray-800 font-poppins shadow-xl cursor-pointer transition-all duration-500 ease-in-out hover:shadow-2xl"
  >
    <div class="w-12 h-12 rounded-full">
      <slot name="company-logo"></slot>
    </div>
    <div class="text-lg md:text-2xl font-medium text-yellow-500 tracking-wide">
      <slot name="company-name"></slot>
    </div>
    <div class="leading-none my-2">
      <div class="text-gray-600 text-sm md:text-base text-justify font-thin">
        <slot name="job-details"></slot>
      </div>
    </div>
    <div class="text-xs text-yellow-500">
      <slot name="job-title"></slot>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>