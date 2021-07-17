<template>
  <div>
      <section class="bg-dark text-white">
          <div class="container-lg">
              <div class="row text-center">
                  <div class="col-12 mt-5">
                        <h5 class="text-uppercase text-info">CUSTOMER TESTIMONIALS</h5>
                        <h2>Trusted<span>Feedback</span></h2>
                       <p class="d-inline-block text-secondary">We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.</p> 
                  </div>
              </div>
              <div class="row mt-5 mb-5 mx-5">
                  <div class="col-4 mb-5" v-for="(element,index) in card" :key="index">              
                    <div class="card animate" >
                        <div class="card-body">
                            <img class="reverse" :src="element.img" alt="">
                            <p class="card-text mt-5">{{element.text}}</p>
                        </div>
                    </div>
                  </div>
              </div>
          </div>
      </section>
  </div>
</template>

<script>
export default {
    name: 'FeedBack',
    data(){
        return{
            card: [
              {
                text : 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium reprehenderit corrupti illo, nihil earum eius tenetur error non natus alias voluptatibus id.',
                img: '/img/logo-1.png'
              }, 
              {
                text : 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet earum vitae aut harum molestias.',
                img: '/img/logo-2.png'
              },
              {
                text : 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium reprehenderit corrupti illo, nihil earum eius tenetur error non natus alias voluptatibus id.',
                img: '/img/logo-3.png'
              },  
              ]
        
        }
        }
    }
</script>

<style scoped lang="scss">
p{
    width: 70%;
    margin-right: 100px;
}
h2{
    font-size: 50px;
    font-weight: bold;
    span{
            border-radius: 5px;
            color: #058283 ;
            background-color: #0fffff23;
        }
}
.card{
    background-color: #1D1D23;
    width: 24rem;
    padding: 30px;
    height: 25rem;
}
.reverse{
    filter: invert(1);
}

</style>