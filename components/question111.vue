<template>
  <div class="question111-container" v-bind:class="rootClassName">
    <span class="question111-text1 heading3">{{ question }}</span>
    <span class="bodySmall">{{ answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question111',
  props: {
    answer: {
      type: String,
      default:
        'Nasza wypożyczalnia oferuje elastyczne opcje wynajmu na krótkie i długie okresy. Możesz wynająć rower na godziny, dni lub tygodnie, a nasz zespół pomoże Ci wybrać odpowiedni model zgodnie z Twoimi potrzebami i preferencjami.',
    },
    question: {
      type: String,
      default: 'Jakie są zasady i opcje wynajmu rowerów w Waszej wypożyczalni?',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.question111-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question111-text1 {
  font-weight: 700;
}

</style>
