<template>
  <div class="home">
    <Slider />
    <HomeItems />
    <Footer />
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";
import Slider from "@/components/Slider.vue";
import HomeItems from "@/components/HomeItems.vue"; // @ is an alias to /src
import Footer from "@/components/Footer.vue";
</script>
