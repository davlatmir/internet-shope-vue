<template>
  <div id="app">
    <p>Hello Vue</p>
  </div>
  <v-main-wrapper></v-main-wrapper>
</template>

<script>
import vMainWrapper from './components/v-main-wrapper.vue'
export default {
  name: 'app',
  components: { vMainWrapper },
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 160px;
}
</style>
