<template>
  <div class="v-catalog.vue">
    <h1>Catalog</h1>
    <v-catalog-item></v-catalog-item>
  </div>
</template>
  
  <script>
import vCatalogItemVue from "./v-catalog-item.vue";

export default {
    components: {
    vCatalogItemVue,
  },
  name: "v-catalog.vue",
  props: {},
  data() {
    return {};
  },
};
</script>
  
  <style>
</style>