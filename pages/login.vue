<template>
  <div class="login-container1">
    <div class="login-container2">
      <nuxt-link to="/" class="login-logo">BIKEMANIA</nuxt-link>
    </div>
    <sign-in1></sign-in1>
  </div>
</template>

<script>
import SignIn1 from '../components/sign-in1'

export default {
  name: 'Login',
  components: {
    SignIn1,
  },
  head: {
    title: 'BikeMania',
  },
}
</script>

<style scoped>
.login-container1 {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #202020;
}
.login-container2 {
  flex: 0 0 auto;
  width: 100%;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.login-logo {
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
