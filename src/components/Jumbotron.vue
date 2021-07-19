<template>
  <div>
     <img src="/img/bg-9.jpg" alt="bg-camion">
      <section class="jumbo">
          <div class="container-lg">
              <div class="row">
                  <div class="col-6">
                      <div class="desc">
                      <h5 class="text-info">LOGISTICS SERVICES</h5>
                      <h2 class="text-light mt-3 ">CARGO TRANSPORT</h2>
                      <p class="mb-5">Fractional or exclusive road cargo transportation to all regions, with small, medium and large vehicles.</p>
                      <button type="button" class="btn my_btn mx-2 my_light text-uppercase">Get in touch</button>
                      <button type="button" class="btn btn-outline-info mx-2 text-uppercase">Read More</button>
                      </div>
                  </div>
              </div>
          </div>
      </section>
  </div>
</template>

<script>
export default {
name: 'Jumbotron',
}
</script>

<style scoped lang="scss">
img{
    height: 700px;
    width: 100%;
    filter: brightness(0.4);
    position: relative;
}
.desc{
    position: absolute;
    bottom:200px;
    h2{
        font-size: 72px;
        width: 100px;
        font-weight: 700;
    }
    p{
        color: gray;
        font-size: 19.2px;
        width: 800px;
    }
}
</style>