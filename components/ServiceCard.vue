<template>
  <article class="bg-white border border-gray-200 rounded-2xl p-8 flex flex-col gap-4 shadow-sm">
    <h3 class="text-xl font-bold text-slate-900">{{ title }}</h3>
    <p class="text-slate-600 leading-relaxed">{{ description }}</p>
    <ul class="space-y-2">
      <li
        v-for="item in items"
        :key="item"
        class="flex items-center gap-2 text-slate-600 text-sm"
      >
        <span class="w-1.5 h-1.5 rounded-full bg-accent shrink-0"></span>
        {{ item }}
      </li>
    </ul>
    <NuxtLink
      :to="link"
      class="mt-auto inline-flex items-center gap-1.5 text-brand font-semibold text-sm hover:text-brand-dark transition-colors"
    >
      Læs mere →
    </NuxtLink>
  </article>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  items: {
    type: Array,
    default: () => []
  },
  link: String
})
</script>
