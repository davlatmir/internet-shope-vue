<template>
  <div class="v-main-wrapper.vue">
    <p>{{title}}</p>
  </div>
</template>

<script>


export default {
    name: 'v-main-wrapper.vue',
    data() {
        return {
            title: 'Main wrapper'
        }
    },
}
</script>

<style>
.v-main-wrapper.vue{
    display: flex;
    justify-content: center;
    align-content: center;
    max-width: 900px;
    margin: 0 auto;
}

</style>