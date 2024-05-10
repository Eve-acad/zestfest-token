<template>
  <div class="p-6 2xl:px-40 container xl:mx-auto flex justify-between items-center min-w-full">
    <img src="@/assets/logo.svg" />
    <div class="hidden xl:flex text-sm items-center">
      <div class="flex gap-8">
        <a href="https://dexscreener.com/"><div class="flex gap-1.5">Chart </div></a>
        <a href="https://t.me/zestfestsol"><div class="flex gap-1.5">Telegram</div></a>
        <a href="https://twitter.com/"><div class="flex gap-1.5">Twitter</div></a>
        <a href="https://solscan.io/token/"><div class="flex gap-1.5">Solscan </div></a>

      </div>
        <a href="https://www.pump.fun/board">
      <button
        class="mx-5 px-4 text-xs gradient-blue text-white rounded-[4px] py-3 hover:border-[#3040E8] font-semibold border hover:text-[#1829d9]"
      >
        Book Now
      </button></a>
    </div>
    <Menu class="xl:hidden w-12 h-12 cursor-pointer" />
  </div>
</template>

<script setup lang="ts">
import { Menu, ChevronDown } from 'lucide-vue-next'
</script>
