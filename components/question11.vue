<template>
  <div class="question11-container" v-bind:class="rootClassName">
    <span class="question11-text1 heading3">{{ question }}</span>
    <span class="bodySmall">{{ answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question11',
  props: {
    rootClassName: String,
    answer: {
      type: String,
      default:
        'Tak, w "BikeMania" zapewniamy kompleksowe usługi serwisowe i konserwacyjne dla wszystkich rowerów zakupionych u nas. Nasz doświadczony zespół mechaników zadba o Twój rower, aby działał sprawnie i bezpiecznie.',
    },
    question: {
      type: String,
      default:
        'Czy oferujecie usługi serwisowe i konserwacyjne dla rowerów zakupionych w sklepie?',
    },
  },
}
</script>

<style scoped>
.question11-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question11-text1 {
  font-weight: 700;
}

</style>
