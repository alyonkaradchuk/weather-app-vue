<template>
  <div
    class="flex flex-col min-h-screen font-Roboto bg-weather-primary"
  >
    <SiteNavigation />
    <RouterView />
    <!-- <FooterWaves/> -->
  </div>
</template>

<script setup>
import { RouterView } from "vue-router";
import SiteNavigation from "./components/SiteNavigation.vue";
// import FooterWaves from "./components/FooterWaves.vue";
</script>

<style lang="scss" scoped></style>