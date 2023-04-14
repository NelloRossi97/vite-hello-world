<template>
  <div>
    <AppNav />
    <AppHero />
  </div>
  
</template>

<script>
import AppNav from './components/AppNav.vue';
import AppHero from './components/AppHero.vue';
  export default {
    name: 'App',
    components: {
      AppNav,
      AppHero
    }
  }
</script>

<style lang="scss" scoped>

</style>