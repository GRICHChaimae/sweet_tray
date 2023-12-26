
<template>
  <div class="grid grid-cols-3 m-4 gap-2">
    <div v-for="card in card_data" :key="card.key">
      <ShowcaseCard :name="card.name" :chef="card.chef" :imgPath="card.imgPath" />
    </div>
  </div>
</template>

  <script setup>
  import ShowcaseCard from './components/ShowcaseCard.vue';

  const card_data = [{
    key: 1,
    name: "Choco ball with pistachio",
    chef: "By chef Eric",
    imgPath: "src/assets/img/showcase1.jpg"
  },
  {
    key: 2,
    name: "Choco ball with pistachio",
    chef: "By chef Patesrie",
    imgPath: "src/assets/img/showcase2.jpg"
  },
  {
    key: 3,
    name: "Choco ball with pistachio",
    chef: "By chef Donuts",
    imgPath: "src/assets/img/showcase3.jpg"
  },
]
  </script>

