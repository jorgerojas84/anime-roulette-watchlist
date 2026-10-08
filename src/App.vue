<script setup>
import NavMenu from '@/components/NavMenu.vue'
</script>

<template>
  <div class="h-screen flex flex-col">
    <NavMenu />
    <RouterView />
  </div>
</template>
