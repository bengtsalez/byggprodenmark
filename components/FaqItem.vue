<template>
  <details class="group bg-white border border-gray-200 rounded-2xl px-6 py-4 cursor-pointer">
    <summary class="font-semibold text-slate-900 list-none flex items-center justify-between gap-4 select-none">
      {{ question }}
      <span class="text-brand text-xl leading-none shrink-0 transition-transform group-open:rotate-45">+</span>
    </summary>
    <div class="mt-3 text-slate-500 text-sm leading-relaxed">
      <slot />
    </div>
  </details>
</template>

<script setup>
defineProps({
  question: String
})
</script>
