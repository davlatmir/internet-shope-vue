<template>
  <div class="v-main-wrapper.vue">
    <p>{{ title }}</p>
  </div>
  <v-catalog></v-catalog>
  <v-cart></v-cart>
</template>

<script>
import vCatalog from "./v-catalog.vue";
import VCart from "./v-cart.vue";

export default {
  components: { vCatalog, VCart },
  name: "v-main-wrapper.vue",
  data() {
    return {
      title: "Main wrapper",
    };
  },
};
</script>

<style>
.v-main-wrapper.vue {
  display: flex;
  justify-content: center;
  align-content: center;
  max-width: 900px;
  margin: 0 auto;
}
</style>