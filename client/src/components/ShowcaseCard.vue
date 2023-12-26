<template>
  <card class="card grid col-span-1">
    <img :src="imgPath" alt="chco_ball" class="w-full h-48 object-cover">
    <div class="p-2">
      <span>{{ name }}</span>
      <span class="block">{{ chef }}</span>
    </div>
    <div class="price">
      <span>15 $</span>
    </div>
  </card>
</template>

<script setup>
  defineProps({
    name: String,
    chef: String,
    imgPath: String
  })

</script>

<style>

</style>