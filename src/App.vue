<script setup>
import NavbarComp from '@/components/NavbarComp.vue'
import FooterComp from '@/components/FooterComp.vue'
</script>

<template>
  <div>
    <NavbarComp class="nav" />
    <router-view />
    <FooterComp />
  </div>
</template>

<style lang="scss" scoped>
@import '@/assets/_shared.scss';

* {
  margin: 0;
  padding: 0;
  font-family: 'Nunito Sans', sans-serif;
}

html {
  scroll-behavior: smooth;
}
</style>
