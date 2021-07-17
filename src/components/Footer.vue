<template>
  <section class="bg-dark mt-5">
      <div class="container-lg">
          <div class="row">
               <div class="row mt-5 mb-5">
                  <div class="col-3">              
                    <div class="card text-secondary animate">
                        <div class="card-body">
                            <div class="logo">
                                <h1 class="text-uppercase text-light fs-3"><span class="text-info">Nex</span>gen</h1>
                            </div>
                        </div>
                            <div class="mt-3 contact"><i class="fas fa-phone-alt"></i>3335557776</div>
                            <div class="mt-3 contact"><i class="fas fa-envelope-open"></i>mail@example.com</div>
                            <div class="mt-3 contact"><i class="fas fa-map-marker-alt"></i>Main Avenue, 123</div>
                            <button type="button" class="btn btn-outline-info mt-4 mb-3">Get in touch</button>
                    </div>
                  </div>
                  <div class="col-3">              
                    <div class="card animate text-secondary">
                        <div class="card-body mt-1" >
                            <h2 class="text-light">Company</h2>
                            <ul v-for="(element,index) in company" :key="index">
                                <li>{{element.text}}</li>
                            </ul>
                        </div>
                    </div>
                  </div>
                  <div class="col-3">              
                    <div class="card animate text-secondary">
                        <div class="card-body mt-1" >
                            <h2 class="text-light">Transport</h2>
                            <ul v-for="(element,index) in transport" :key="index">
                                <li>{{element.text}}</li>
                            </ul>
                        </div>
                    </div>
                  </div>
                  <div class="col-3">              
                    <div class="card animate text-secondary">
                        <div class="card-body mt-1" >
                            <h2 class="text-light">Support</h2>
                            <ul v-for="(element,index) in support" :key="index">
                                <li>{{element.text}}</li>
                            </ul>
                        </div>
                    </div>
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
name: 'Footer',
data() {
    return {
      company: [
      {
        text : 'The Company',
      }, 
      {
        text : 'Istitutional',
      },
      {
        text : 'Social & Events',
      }, 
      {
        text : 'Innovation',
      }, 
      {
        text : 'Envionment',
      },  
      {
        text : 'Technology',
      },  
      ],
      transport: [
      {
        text : 'Industrialized',
      }, 
      {
        text : 'Chemicals',
      },
      {
        text : 'Packaged Liquids',
      }, 
      {
        text : 'Construction',
      }, 
      {
        text : 'Laminated Wood',
      },  
      {
        text : 'And others',
      },  
      ],
      support: [
      {
        text : 'Responsability',
      }, 
      {
        text : 'Therms of Use',
      },
      {
        text : 'About Cookies',
      }, 
      {
        text : 'Privacy Policy',
      }, 
      {
        text : 'Accessibility',
      },  
      {
        text : 'Information',
      },  
      ]
    }

  }
}
</script>

<style scoped lang="scss">
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
.card{
    background-color: #1D1D23;
    width: 18rem;
    padding: 30px;
    height: 22rem;
}
button{
    width: 50%;
}
.contact:hover{
    color: #058283;
}


</style>