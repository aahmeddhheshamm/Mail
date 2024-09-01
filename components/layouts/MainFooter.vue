<script setup>
import FooterBg from "assets/images/footer-background.png";

</script>

<template>
  <div class="md:mx-[120px]">
    <div
        class="cover-store-profile h-[580px] relative rounded-t-[40px]"
        :style="{
        'background-image': 'url(' + FooterBg + ')',
        'background-size': 'cover',
        'background-position': 'center',
        'background-repeat': 'no-repeat'
      }"
    >
      <div class="flex items-center justify-between h-full relative z-10 ps-[55px] my-auto">
        <div class="flex flex-col gap-[24px]">
          <p class="md:text-[64px] text-[24px] font-bold leading-[62px] text-white max-w-[613px]">
            Download Mails App
          </p>
          <p class="md:text-[24px] text-[14px] font-medium leading-[25px] text-white max-w-[766px]">
            Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg
          </p>
          <p class="md:text-[24px] text-[14px] font-medium leading-[25px] text-white max-w-[766px]">
            Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg
          </p>
          <p class="md:text-[24px] text-[14px] font-medium leading-[25px] text-white max-w-[766px]">
            Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg
          </p>
        </div>

        <div class="lg:absolute top-[-100px] right-0">
          <img src="@/assets/images/mobile-footer.png" class="" />
        </div>
      </div>

    </div>

  </div>
</template>

<style>
.social--icon path{
  fill: #7D818D!important
}
.social--icon:hover path{
  fill: #68D585!important;
}
.social--icon:hover rect{
  fill: #68D585!important;
}

</style>

