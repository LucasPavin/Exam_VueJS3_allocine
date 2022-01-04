<template>
  <div class="col-xs-12 col-sm-12 col-md-4 item">
    <div class="block-img">
      <img :src="homeItemModel.image" />
    </div>
    <div class="content-text">
      <p class="title-item title">{{ homeItemModel.titre }}</p>
      <p class="text-item">{{ homeItemModel.texte }}</p>
    </div>
  </div>
</template>
<script setup lang="ts">
import { defineProps } from "vue";
import { HomeItemModel } from "@/models/HomeItemModel";

defineProps<{
  homeItemModel: HomeItemModel;
}>();
</script>

<style scoped>
.item .block-img img {
  width: 120px;
}
img {
  max-width: 100%;
}
</style>
