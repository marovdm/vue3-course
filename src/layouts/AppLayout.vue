<template>
  <div>
    <app-header />
    <slot />
  </div>
</template>

<script setup>
import AppHeader from "./AppHeader.vue";
</script>

<style lang="scss" scoped>
.app_layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}
</style>