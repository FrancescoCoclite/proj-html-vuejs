<template>
  <div>
      <section class="bg-dark text-white mt-5">
          <div class="container-lg">
              <div class="row">
                  <div class="col-12 mt-5">
                      <h5 class="text-uppercase text-info">Road Transport</h5>
                      <h2><span>Main</span> Services</h2>
                      <div>
                        <p class="d-inline-block text-secondary">With all of this expertise and capability comes an unrivalled commitment to customer service. We will work hard to understand your needs in order to develop a productive, long-term partnership. </p> 
                        <button type="button" class="btn btn-outline-info d-iline-block p-2">Read More</button>  
                      </div>
                  </div>
              </div>
              <div class="row mt-5 mb-5">
                  <div class="col-4 mb-5" v-for="(element,index) in servizi" :key="index">              
                    <div class="card animate">
                        <div class="card-body">
                            <div class="d-flex justify-content-between">
                            <span class="pulse icone"><i :class="element.icona"></i></span><span class="fs-3 text-info"><i :class="element.freccia"></i></span>                            </div>
                            <h5 class="card-title mt-5">{{element.titolo}}</h5>
                            <p class="card-text">{{element.desc}}</p>
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
    name: 'MainServices',
    data(){
        return{
            servizi : [
                {
                    icona: 'fas fa-truck-loading',
                    titolo: 'Technology',
                    desc: 'We are continually focused on developing technology solutions adapted to our client\'s needs.',
                    freccia: 'fas fa-arrow-right pulse'

                },
                {
                    icona: 'fas fa-temperature-high',
                    titolo: 'Refeer Cargo',
                    desc: 'Regular and frequent monitoring from the receipt of the loaded container to final destination.',
                    freccia: 'fas fa-arrow-right pulse'

                },
                {
                    icona: 'fas fa-boxes',
                    titolo: 'Dry cargo',
                    desc: 'We work with most types of dry cargo, from valuable cargo to the most dangerous requiring care.',
                    freccia: 'fas fa-arrow-right pulse'

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
button{
    padding:0px;
}
.card{
    background-color: #1D1D23;
    width: 24rem;
    padding: 30px;
    height: 22rem;
}
.icone{
            height: 50px;
            width: 50px;
            display: table-cell;
            text-align: center;
            vertical-align: middle;
            border-radius: 50%;
            background: #058283;
            font-size: 30px;
}
</style>