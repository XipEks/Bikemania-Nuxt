<template>
  <div class="question1111-container" v-bind:class="rootClassName">
    <span class="question1111-text1 heading3">{{ question }}</span>
    <span class="bodySmall">{{ answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question1111',
  props: {
    answer: {
      type: String,
      default:
        'Tak, "BikeMania" posiada bogaty asortyment akcesoriów i części zamiennych do różnych modeli rowerów. Oferujemy kaski, oświetlenie, torby, blokady, bagażniki oraz wiele innych produktów, abyś mógł dostosować swój rower do swoich potrzeb.',
    },
    rootClassName: String,
    question: {
      type: String,
      default:
        'Czy w sklepie można znaleźć akcesoria i części zamienne do różnych modeli rowerów?',
    },
  },
}
</script>

<style scoped>
.question1111-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question1111-text1 {
  font-weight: 700;
}

</style>
