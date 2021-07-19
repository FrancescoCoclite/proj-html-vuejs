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
    <Footer/>
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
 import Footer from './components/Footer.vue'


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
    Footer,

  }
}
</script>

<style lang="scss">
@import '@/style/general.scss';
@import '@/style/commons.scss';
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200&display=swap');

</style>
