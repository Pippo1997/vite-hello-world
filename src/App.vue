<script>
  import AppTitle from './components/AppTitle.vue';
  export default{
    components:{
      AppTitle
    },
    data() {
      return {
        title: `la mia prima app con vue`
      }
    },
  }
</script>

<template>
  <div>
    <AppTitle></AppTitle>
  </div>
</template>

<style scoped>

</style>

