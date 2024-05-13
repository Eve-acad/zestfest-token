<template>
  <div class="p-6 2xl:px-40 container xl:mx-auto flex justify-between items-center min-w-full">
    <img src="@/assets/drake.png" style="width: 100px; height: 60px" />
    <div class="hidden xl:flex text-sm items-center">
      <div class="flex gap-8">
        <a href="https://dexscreener.com/solana/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f"><div class="flex gap-1.5">ZestScreener</div></a>
        <a href="https://t.me/zestfestsol"><div class="flex gap-1.5">ZestyGram</div></a>
        <a href="https://twitter.com/zestfestsolana"><div class="flex gap-1.5">ZesTwitter</div></a>
        <a href="https://solscan.io/token/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f"><div class="flex gap-1.5">ZestyScan</div></a>
      </div>
      <a href="https://www.pump.fun/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f">
        <button
          class="zest mx-5 px-4 text-xs gradient-blue text-white rounded-[4px] py-3 hover:border-[#3040E8] border hover:text-[#1829d9]"
          style="font-size: 30px"
        >
          I WANT TO COME TO ZEST FEST
        </button></a
      >
    </div>
    <Menu class="xl:hidden w-12 h-12 cursor-pointer" @click="show = !show" />
  </div>
  <div class="relative xl:hidden" v-if="show">
    <div class="absolute w-full bg-white flex flex-col items-center gap-3 py-3">
      <a href="https://dexscreener.com/solana/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f"><div class="flex gap-1.5">ZestyChart</div></a>
      <a href="https://t.me/zestfestsol"><div class="flex gap-1.5">ZestyGram</div></a>
      <a href="https://twitter.com/zestfestsolana"><div class="flex gap-1.5">ZesTwitter</div></a>
      <a href="https://solscan.io/token/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f"><div class="flex gap-1.5">ZestyScan</div></a>
      <a href="https://www.pump.fun/8m8YSa6q3SB7z8yp3ecL13XvkqxFD24p3pb95DmgPo1f">
      <button
        class="zest mx-5 px-4 text-xs gradient-blue text-white rounded-[4px] py-3 hover:border-[#3040E8] border hover:text-[#1829d9]" style="font-size: 30px"
      >
        I WANT TO COME TO ZEST FEST
      </button></a>
    </div>
  </div>
</template>

<script setup lang="ts">
import { Menu } from 'lucide-vue-next'
import { ref } from 'vue'

const show = ref(false)
</script>
