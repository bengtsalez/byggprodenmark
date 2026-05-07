<template>
  <article class="service-card">
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
    <ul>
      <li v-for="item in items" :key="item">{{ item }}</li>
    </ul>
    <NuxtLink :to="link" class="btn btn-secondary">Læs mere</NuxtLink>
  </article>
</template>

<script setup>
const props = defineProps({
  title: String,
  description: String,
  items: {
    type: Array,
    default: () => []
  },
  link: String
})
</script>
