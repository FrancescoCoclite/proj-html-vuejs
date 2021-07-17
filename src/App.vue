<template>
  <div id="app">
    <Nav/>
    <Jumbotron/>
    <Main/>
    <MainServices/>
    <Logical/>
    <Counter/>
    <FeedBack/>
    <Form/>
  </div>
</template>
<script>
 import Nav from './components/Nav.vue'
 import Jumbotron from './components/Jumbotron.vue'
 import Main from './components/Main.vue'
 import MainServices from './components/MainServices.vue'
 import Logical from './components/Logical.vue'
 import Counter from './components/Counter.vue'
 import FeedBack from './components/FeedBack.vue'
 import Form from './components/Form.vue'
 

export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Jumbotron,
    MainServices,
    Logical,
    Counter,
    FeedBack,
    Form,
  }
}
</script>

<style lang="scss">
@import '@/style/general.scss';
@import '@/style/commons.scss';

</style>
