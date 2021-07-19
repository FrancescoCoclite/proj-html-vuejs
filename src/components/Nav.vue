<template>
<section>
    <div class="container-lg text-light">
    <header>
      <div class="logo mt-3">
        <h1 class="text-uppercase text-light fs-3"><span class="text-info">Nex</span>gen</h1>
      </div>
      <nav>
        <ul class="mt-3">
          <li v-for="(link,index) in link" :key="index" class="dropdown">
            <a href="#" class="text-light">{{link.text}}</a><i class="fas fa-chevron-down"></i>
            <div class="dropdown-content">
              <ul v-if="link.subitems"> 
                <li v-for="(element, index) in link.subitems" :key="index">
                    <a class="text-light">{{element.text}}</a>
                </li>
            </ul>
            </div>
          </li>
            <i class="far fa-user"></i>
            <button type="button" class="btn my_btn mx-2 text-uppercase">Get in touch</button>
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
      link: [
      {
        text : 'Home',
        subitems: [
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
        ]
      }, 
      {
        text : 'About',
        subitems: [
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
        ]
      },
      {
        text : 'Service',
        subitems: [
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
        ]
      }, 
      {
        text : 'Process',
        subitems: [
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
        ]
      }, 
      {
        text : 'Testimonials',
        subitems: [
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
          {
            text : 'Link array',
          },
        ]
      },  
      ]

    }

  }
}
</script>


<style scoped lang="scss">
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  top: 50px;
  left: 0px;
  width: 100px;
  background: #132f438a;
  line-height: 40px;
  ul{
    width: 150px;
    padding: 0;
  }
  
}
.dropdown:hover .dropdown-content {
  display: block;
  

}
section{
  position: fixed;
  z-index: 9999;
  width: 100%;
  background-color: #132f438a;
}
.container{
  width: 1080px;
  margin: auto;
}
a{
  text-decoration: none;
  margin-right: 5px;
}
header{
  height: 60px;
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