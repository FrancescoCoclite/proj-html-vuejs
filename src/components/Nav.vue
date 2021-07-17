<template>
<section>
    <div class="container-lg p-1 text-light">
    <header>
      <div class="logo mt-3">
        <h1 class="text-uppercase text-light fs-3"><span class="text-info">Nex</span>gen</h1>
      </div>
      <nav>
        <ul class="mt-3">
          <li v-for="(link,index) in links" :key="index"><a href="#" class="text-light">{{link.text}}</a></li>
            <i class="far fa-user"></i>
            <button type="button" class="btn my_btn mx-2">Get in touch</button>
        </ul>
      </nav>
    </header>
    </div>
</section>
</template>

<script>
export default {
  name: 'Nav',
 
  data() {
    return {
      links: [
      {
        text : 'Home',
      }, 
      {
        text : 'About',
      },
      {
        text : 'Service',
      }, 
      {
        text : 'Process',
      }, 
      {
        text : 'Testimonials',
      },  
      ]

    }

  }
}
</script>


<style scoped lang="scss">
section{
  position: fixed;
  z-index: 9999;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.767);
}
.container{
  width: 1080px;
  margin: auto;
}
a{
  text-decoration: none;
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
   h1{
     
    background-image: linear-gradient(left , rgba(0, 247, 255, 0.192) 50%, rgb(255, 255, 0) 100%);
    background-image: -o-linear-gradient(left , rgba(0, 247, 255, 0.192) 50%, rgb(255, 255, 0) 100%);
    background-image: -moz-linear-gradient(left , rgba(0, 247, 255, 0.192) 50%, rgb(255, 255, 0) 100%);
    background-image: -webkit-linear-gradient(left , rgba(0, 247, 255, 0.192) 50%, rgb(255, 255, 0) 100%);
    background-image: -ms-linear-gradient(left , rgba(0, 247, 255, 0.192) 50%, rgba(255, 255, 255, 0) 100%);
    border-radius: 10px;

  background-image: -webkit-gradient(
    linear,
    left bottom,
    right bottom,
    color-stop(0.5, rgba(0, 247, 255, 0.192)),
    color-stop(0.51, rgba(255, 255, 255, 0))
);
   }
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