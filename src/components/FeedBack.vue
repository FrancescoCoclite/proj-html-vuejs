<template>
  <div>
      <section class="bg-dark text-white">
          <div class="container-lg">
              <div class="row text-center">
                  <div class="col-12 mt-5">
                        <h5 class="text-uppercase text-info">CUSTOMER TESTIMONIALS</h5>
                        <h2>Trusted Feedback</h2>
                       <p class="d-inline-block text-secondary">We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.</p> 
                  </div>
              </div>
              <div class="row mt-5 mb-5 mx-5">
                  <div class="col-4">              
                    <div class="card animate">
                        <div class="card-body">
                            <img class="reverse" src="img/logo-1.png" alt="">
                            <p class="card-text mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium reprehenderit corrupti illo, nihil earum eius tenetur error non natus alias voluptatibus id.</p>
                        </div>
                    </div>
                  </div>
                  <div class="col-4 mb-5">              
                    <div class="card animate">
                        <div class="card-body">
                            <img class="reverse" src="img/logo-2.png" alt="">
                            <p class="card-text mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium reprehenderit corrupti illo, nihil earum eius tenetur error non natus alias voluptatibus id.</p>
                        </div>
                    </div>
                  </div>
                  <div class="col-4 mb-5">              
                        <div class="card animate">
                            <div class="card-body">
                                <img class="reverse" src="img/logo-3.png" alt="">
                                <p class="card-text mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium reprehenderit corrupti illo, nihil earum eius tenetur error non natus alias voluptatibus id.</p>
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
.card{
    background-color: #1D1D23;
    width: 24rem;
    padding: 30px;
    height: 22rem;
}
.reverse{
    filter: invert(1);
}

</style>