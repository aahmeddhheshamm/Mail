<script setup>
import MailsBg from '@/assets/images/mails-background.jpeg'</script>
<template>

  <div
      class="cover-store-profile h-[982px] relative"
      :style="{
        'background-image': 'url(' + MailsBg + ')',
        'background-size': 'cover',
        'background-position': 'center',
        'background-repeat': 'no-repeat'
      }"
  >
    <div class="flex items-center justify-between flex-wrap h-full relative z-10 md:px-[116px] px-[40px] my-auto">
      <div class="flex flex-col md:gap-[24px] gap-[16px]">
        <p class="md:text-[48px] text-[24px] font-medium leading-[62px] text-white max-w-[596px]">
          Download app,
          Get discounts for your car
        </p>
        <p class="md:text-[20px] text-[14px] font-medium leading-[25px] text-white">
          Download the application, turn on the meter, start your journey, and get your discounts
        </p>
        <div class="flex items-center gap-[16px] flex-wrap ">
          <img src="@/assets/images/google-play.png" />
          <img src="@/assets/images/app-store.png" />
        </div>
      </div>

      <img src="@/assets/images/mobile-header.png" />
    </div>

  </div>
</template>
<style scoped>

.cover-store-profile::after {
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.90)0%, rgba(0, 0, 0, 0.00)100%);
  position: absolute;
  top: 0;
  left: 0;
  content: "";
  width: 100%;
  height: 100%;
}
</style>
