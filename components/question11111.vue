<template>
  <div class="question11111-container" v-bind:class="rootClassName">
    <span class="question11111-text1 heading3">{{ question }}</span>
    <span class="bodySmall">{{ answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question11111',
  props: {
    question: {
      type: String,
      default:
        'Czy macie program lojalnościowy lub oferujecie zniżki dla stałych klientów?',
    },
    answer: {
      type: String,
      default:
        'Tak, w "BikeMania" cenimy naszych stałych klientów i oferujemy program lojalnościowy, który zapewnia zniżki i specjalne oferty. Zapraszamy do dołączenia do naszego programu, aby korzystać z dodatkowych korzyści przy każdych zakupach.',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.question11111-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question11111-text1 {
  font-weight: 700;
}

</style>
