<template>
  <div class="rejestracja-container1">
    <div class="rejestracja-container2">
      <nuxt-link to="/" class="rejestracja-logo">BIKEMANIA</nuxt-link>
    </div>
    <sign-up1></sign-up1>
  </div>
</template>

<script>
import SignUp1 from '../components/sign-up1'

export default {
  name: 'Rejestracja',
  props: {},
  components: {
    SignUp1,
  },
  head: {
    title: 'Rejestracja - BikeMania',
    meta: [
      {
        property: 'og:title',
        content: 'Rejestracja - BikeMania',
      },
    ],
  },
}
</script>

<style scoped>
.rejestracja-container1 {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: #202020;
}
.rejestracja-container2 {
  flex: 0 0 auto;
  width: 100%;
  height: 100px;
  display: flex;
  margin-top: var(--dl-space-space-threeunits);
  align-items: center;
  justify-content: flex-start;
}
.rejestracja-logo {
  color: #ffffff;
  font-size: 3em;
  font-family: Hind;
  font-weight: 700;
  line-height: 150%;
  margin-left: var(--dl-space-space-fiveunits);
  text-transform: uppercase;
  text-decoration: none;
}
</style>
