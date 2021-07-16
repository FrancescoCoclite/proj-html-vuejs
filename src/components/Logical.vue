<template>
  <div>
      <section>
          <div class="container-fluid mt-5">
              <div class="row">
                  <div class="col-12 text-center">
                      <h5 class="text-uppercase">How it's work in practice</h5>
                      <h2><span>Logistical</span> Procedure</h2>
                      <p>We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.</p>
                  </div>
              </div>
              <div class="row mt-5">
                  <div class="col-4 d-flex"><span class="linea"></span><div class="numeri">1</div><span class="linea"></span><div class="numeri">2</div></div>
                  <div class="col-4 d-flex"><span class="linea"></span><div class="numeri">3</div><span class="linea"></span></div>
                  <div class="col-4 d-flex"><div class="numeri">4</div><span class="linea"></span><div class="numeri">5</div><span class="linea"></span></div>
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
span{
    border-radius: 5px;
    color: #058283 ;
    background-color: #0fffff23;
}
.numeri{
    background: #CCE3DE;
    padding: 20px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    line-height: 0px;
}
</style>