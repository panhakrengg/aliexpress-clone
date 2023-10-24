import { Icon } from '../.nuxt/components';
<template lang="">
  <div id="MainLayout" class="w-full fix z-50">
    <div id="TopMenu" class="w-full bg-[#FAFAFA] fixed z-50">
      <ul
        class="flex items-center justify-end text-xs text-[#333333] font-light px-2 h-10 bg-[#FAFAFA] max-w-[1200px]"
      >
        <li
          class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer"
        >
          Sell on AliExpress
        </li>
        <li
          class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer"
        >
          Cookie Preference
        </li>
        <li
          class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer"
        >
          Help
        </li>
        <li
          class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer"
        >
          Buy Protection
        </li>
        <li class="px-3 hover:text-[#FF4646] cursor-pointer">
          <Icon name="ic:sharp-install-mobile" size="17" />
          App
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang=""></style>
