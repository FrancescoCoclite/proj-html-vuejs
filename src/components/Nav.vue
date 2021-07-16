<template>
  <div id="box ">
    <div class="container-lg mt-3">
    <header>
      <div class="logo">
        <h1 class="text-uppercase text-light fs-3"><span>Nex</span>gen</h1>
      </div>
      <nav>
        <ul>
          <li v-for="(link,index) in links" :key="index"><a href="#"></a>{{link.text}}</li>
            <i class="far fa-user"></i>
            <button type="button" class="btn my_btn mx-2">Get in touch</button>
        </ul>
      </nav>
    </header>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
 
  data() {
    return {
      links: [
      {
        text : 'Home',
        url : '#',
        status : false,
      }, 
      {
        text : 'About',
        url : '#',
        status : false,
      },
      {
        text : 'Service',
        url : '#',
        status : false,
      }, 
      {
        text : 'Process',
        url : '#',
        status : false,
      }, 
      {
        text : 'Testimonials',
        url : '#',
        status : false,
      },  
      ]

    }

  }
}
</script>


<style scoped lang="scss">
.container{
  width: 1080px;
  margin: auto;
}
span{
    border-radius: 30px;
    padding-left: 10px;
    padding-right: 10px;
    color: #058283 ;
    background-color: #0fffff23;
}

header{
  height: 70px;
  &::after{
    display: table;
    content: '';
    clear: both;
  }
  .logo{
   float: left; 
  }
  nav{
    float: right;
    li {
      
      display: inline-block;
      margin: 0 10px;
      
    }
    a{
      color: black;
    }
  }
}

</style>