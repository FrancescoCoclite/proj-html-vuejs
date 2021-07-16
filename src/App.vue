<template>
  <div id="app">
    <Nav/>
    <Jumbotron/>
    <Main/>
  </div>
</template>
<script>
 import Main from './components/Main.vue'
 import Nav from './components/Nav.vue'
 import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Jumbotron,
  }
}
</script>

<style lang="scss">
@import '@/style/general.scss';
@import '@/style/commons.scss';

</style>
