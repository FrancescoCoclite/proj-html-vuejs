<template>
  <div>
      <section class="mb-5 mt-5">
          <div class="container-fluid mt-5">
              <div class="row">
                  <div class="col-12 text-center p-3">
                      <h5 class="text-uppercase text-info">How it's work in practice</h5>
                      <h2><span>Logistical</span> Procedure</h2>
                      <p>We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.</p>
                  </div>
              </div>
              <div class="row mt-5">
                  <div class="riga"></div>
              </div>
          </div>
          <div class="container-lg">
              <div class="row cols-5">
                  <div class="col-2 descrizione-logical text-center">
                      <h4>1</h4>
                      <h3 class="mt-4">Collection of information</h3>
                      <p>Lorem ipsum dolor sit amet consectetur</p>
                  </div>
                  <div class="col-2 descrizione-logical text-center">
                      <h4>2</h4>
                      <h3 class="mt-4">Service invoice sendig</h3>
                      <p>Lorem ipsum dolor sit amet consectetur</p>
                  </div>
                  <div class="col-2 descrizione-logical text-center">
                      <h4>3</h4>
                      <h3 class="mt-4">Withdrawal of Cargo</h3>
                      <p>Lorem ipsum dolor sit amet consectetur</p>
                  </div>
                  <div class="col-2 descrizione-logical text-center">
                      <h4>4</h4>
                      <h3 class="mt-4">Transport Cunstomer Order</h3>
                      <p>Lorem ipsum dolor sit amet consectetur</p>
                  </div>
                  <div class="col-2 descrizione-logical text-center">
                      <h4>5</h4>
                      <h3 class="mt-4">Successful Delivery</h3>
                      <p>Lorem ipsum dolor sit amet consectetur</p>
                  </div>

              </div>
          </div>
      </section>
  </div>
</template>

<script>
export default {
name: 'Logical',
}
</script>

<style scoped lang="scss">
.linea{
    height: 7px;
    margin-top: 10px;
    width: 500px;
}
h5{
 font-size: 12px;
}
h2{
 font-size: 40px;
 font-weight: 800;
}
p{
    text-align: center;
    font-size: 20px;
}
.riga{
    height: 5px;
    background-color: #CCE3DE;
    position: relative;
    top: 40px;
    z-index: -1;
}
h4{
    text-align: center;
    vertical-align: middle;
    border-radius: 50%;
    margin:auto;
    width: 40px;
    height: 40px;
    background-color: #DAECED;
    color: #058283;
    position: relative;
    z-index: 10;
}
.numeri{
    background: #CCE3DE;
    padding: 20px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    line-height: 0px;
}
.descrizione-logical{
    margin-top: 20px;
    margin-right: 38px;
}
</style>