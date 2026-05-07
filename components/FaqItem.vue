<template>
  <details class="faq-item">
    <summary>{{ question }}</summary>
    <div class="faq-answer">
      <slot />
    </div>
  </details>
</template>

<script setup>
const props = defineProps({
  question: String
})
</script>
