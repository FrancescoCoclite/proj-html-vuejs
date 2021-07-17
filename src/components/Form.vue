<template>
  <div>
      <div class="container-lg">
          <div class="row">
                  <div class="col-8 mt-2 descrizione">
                      <h5 class="text-uppercase text-info">Send a message</h5>
                      <h2>Get in <span>Touch</span></h2>
                      <div>
                        <p class="d-inline-block text-secondary">We will respond to your message as soon as possible. </p>   
                      </div>
                  </div>
              </div>
          <div class="row">
              <div class="col-8">
                    <form>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Inserisci Nome">
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Inserisci Cognome">
                        </div>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Inserisci Email">
                        </div>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="More info">
                        </div>
                            <textarea name="message" id="" cols="112" rows="5" placeholder="Messaggio" class="p-3"></textarea>
                            <button type="button" class="btn rounded-pill btn-outline-info mt-4">Send</button>
                    </form>
              </div>
              
                <div class="col-4 mb-3">              
                    <div class="card border-0">
                        <div class="card-body">
                            <h2>Exmple Inc.</h2>
                            <p class="card-text mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit..</p>
                            <p class="card-text"> Quasi similique voluptatum ut assumenda autem</p>
                            <div class="text-info">
                                <div class="cont mt-2 fs-5"><span class="icone pulse"><i class="fas fa-phone-alt text-info "></i></span>3335557776</div>
                                <div class="cont mt-2 fs-5"><span class="icone pulse"><i class="fas fa-envelope-open text-info "></i></span>mail@example.com</div>
                                <div class="cont mt-2 fs-5"><span class="icone pulse"><i class="fas fa-map-marker-alt text-info "></i></span> Main Avenue, 123</div>
                            </div>
                            <button type="button" class="btn btn-outline-info mt-4">View Map</button>
                        </div>
                    </div>
                </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.descrizione{
    h2{
        font-size: 40px;
        font-weight: 900;
        span{
            border-radius: 5px;
            color: #058283 ;
            background-color: #0fffff23;
        }
    }
}
h2{
    font-size: 24px;
    font-weight: bold;
}
.cont{
    font-size: 23px ;
    line-height: 50px;
    .icone{
            width: 20px;
    height: 20px;
    font-size: 20px;
    line-height: 20px;
    color: #058283;
    background-color: #058283;
    border-radius: 50%;
    fill: #058283;
    padding: 10px 10px 10px 10px;
    margin-right: 20px; 
    margin-top: 10px; 
    }
}
.card{
    padding: 0;
}
.card-body{
    width: 20rem;
}
</style>