<template>
 <div>
     <section>
         <div class="container mt-5">
             <div class="row">
                 <div class="col-7">
                     <h5 class="mb-3 text-uppercase fs-5">who are you</h5>
                     <h2 class="text-uppercase"><span><i class="far fa-gem"></i> Excellence</span> in Transport</h2>
                     <p class="mt-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum velit tortor, interdum sed cursus eu, sagittis ut nunc. Sed vitae tellus et arcu aliquet faucibus fermentum non lacus.</p>
                     <p class="mt-2">Praesent fringilla quis massa et placerat. Mauris eu dui eget urna pellentesque gravida vitae quis nibh. Ut at augue tortor. Pellentesque quis suscipit magna.</p>
                     <p class="p-3 paragrafo">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quam tortor, ultrices accumsan mauris eget, pulvinar tincidunt erat. Sed nisi nisi, rutrum sit amet elit.</p>
                     <ul>
                         <li>Lorem ipsum dolor sit amet</li>
                         <li>Consectetur adipiscing elit</li>
                         <li>Integer molestie lorem at massa</li>
                         <li>Facilisis in pretium nisl aliquet</li>
                     </ul>
                 </div>
                 <div class="col-4 ms-5 ">
                        <h4 class="mb-3 ">Vehicle Types</h4>
                     <div class="box-img d-flex">
                        <img class="d-inline-block" src="/img/truck-1.png" alt="camion">
                        <div>
                            <h3 class="mx-3">Light</h3>
                            <p class="mx-3">Max weight 1200 Kg</p>
                        </div>
                     </div>
                     <div class="box-img d-flex">
                        <img class="d-inline-block" src="/img/truck-1.png" alt="camion">
                        <div>
                            <h3 class="mx-3">Medium</h3>
                            <p class="mx-3">Max weight 6000 Kg</p>
                        </div>
                     </div>
                     <div class="box-img d-flex">
                        <img class="d-inline-block" src="/img/truck-1.png" alt="camion">
                        <div>
                            <h3 class="mx-3">Heavy</h3>
                            <p class="mx-3">Max weight 24000 Kg</p>
                        </div>
                     </div>
                     <h4 class="mt-3"> Certification</h4>
                     <img class="certificato" src="/img/certificate.png" alt="">
                     <img class="certificato" src="/img/certificate.png" alt="">
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
h5{
    color: #058283 ;
}
h2{
    font-size: 40px;
    span{
        border-radius: 5px;
        padding-left: 10px;
        color: #058283 ;
        background-color: #0fffff23;
    }
}
.paragrafo{
    border-left: 5px solid gray
}
img{
    width: 80px;
    height: 60px;
    background-color: #7FD2D5;
}
.box-img{
    border-bottom: 2px solid gray;
}
.certificato{
    width: 100px;
    height: 100px;
    background-color:white;
}
</style>
