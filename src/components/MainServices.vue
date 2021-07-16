<template>
  <div>
      <section class="bg-dark text-white mt-5">
          <div class="container-lg">
              <div class="row">
                  <div class="col-12 mt-5">
                      <h5 class="text-uppercase text-info">Road Transport</h5>
                      <h2>Main Services</h2>
                      <div>
                        <p class="d-inline-block text-secondary">With all of this expertise and capability comes an unrivalled commitment to customer service. We will work hard to understand your needs in order to develop a productive, long-term partnership. </p> 
                        <button type="button" class="btn btn-outline-info d-iline-block p-2">Read More</button>  
                      </div>
                  </div>
              </div>
              <div class="row mt-5 mb-5">
                  <div class="col-4">              
                    <div class="card animate">
                        <div class="card-body">
                            <div class="d-flex justify-content-between">
                            <span class="rounded-circle icone"><i class="fas fa-truck-loading"></i></span><span class="fs-3 text-info"><i class="fas fa-arrow-right"></i></span>

                            </div>
                            <h5 class="card-title mt-5">Technology</h5>
                            <p class="card-text">We are continually focused on developing technology solutions adapted to our client's needs.</p>
                        </div>
                    </div>
                  </div>
                  <div class="col-4 mb-5">              
                    <div class="card animate">
                        <div class="card-body">
                            <div class="d-flex justify-content-between">
                            <span class="rounded-circle icone"><i class="fas fa-temperature-high"></i></span><span class="fs-3 text-info"><i class="fas fa-arrow-right"></i></span>
                            </div>
                            <h5 class="card-title mt-5">Refeer cargo</h5>
                            <p class="card-text">Regular and frequent monitoring from the receipt of the loaded container to final destination.</p>
                        </div>
                    </div>
                  </div>
                  <div class="col-4 mb-5">              
                    <div class="card animate">
                        <div class="card-body">
                            <div class="d-flex justify-content-between">
                            <span class="rounded-circle icone"><i class="fas fa-boxes"></i></span><span class="fs-3 text-info"><i class="fas fa-arrow-right"></i></span>
                            </div>
                            <h5 class="card-title mt-5">Dry cargo</h5>
                            <p class="card-text">We work with most types of dry cargo, from valuable cargo to the most dangerous requiring care.</p>
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
    font-size: 20px;
    background-color: #0fffff23;
    padding: 13px;
    color: #16928E;
}
</style>