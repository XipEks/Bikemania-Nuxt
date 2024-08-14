<template>
  <div class="question1-container">
    <span class="question1-text1 heading3">{{ question }}</span>
    <span class="bodySmall">{{ answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question1',
  props: {
    question: {
      type: String,
      default:
        'Jakie rodzaje rowerów są dostępne w ofercie sklepu "BikeMania"?',
    },
    answer: {
      type: String,
      default:
        'W sklepie "BikeMania" oferujemy szeroki wybór rowerów, w tym górskie, szosowe, miejskie, trekkingowe i elektryczne, aby zaspokoić potrzeby każdego rowerzysty.',
    },
  },
}
</script>

<style scoped>
.question1-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question1-text1 {
  font-weight: 700;
}
</style>
