<template>
  <HeaderComponent />
  <RouterView />
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
import HeaderComponent from '@/components/HeaderComponent.vue'
</script>
