
<template>
  <HeaderApp/>
  <MainApp/>
  <FooterApp/>
</template>

<script>
  import HeaderApp from './components/HeaderApp.vue';
  import FooterApp from './components/FooterApp.vue';
  import MainApp from './components/MainApp.Vue'

  export default{
    name: 'App',
    components: {
      HeaderApp,
      MainApp,
      FooterApp
    }
  }
</script>

<style lang="scss" scoped>
</style>
