<template>
    <div>
        <footer class="d-flex w-100 gap-lg-5">
           <ul class=" mt-4 justify-content-sm-evenly ">
                <li class="link4 linkb text-center">KO`CHA NOMLARI <i class="fas fa-power-off"></i></li>
                <li class="link5 linkb text-center">DAVLAT TASHKILOTLARI <i class="fas fa-power-off"></i></li>
                <li class="link6 linkb text-center">ARXITEKTURA MEROSLARI <i class="fas fa-power-off"></i></li>
                <li class="link7 linkb text-center">ARXEOLOGIYA YODGORLIKLARI <i class="fas fa-power-off"></i></li>
                <li class="link8 linkb text-center">KO`P QAVATLI UYLAR <i class="fas fa-power-off"></i></li>
                <li class="link9 linkb text-center">AHOLI HONADONLARI <i class="fas fa-power-off"></i></li>
           </ul>


           <div class="d-flex position-relative align-items-center">
              <div class="PS d-flex align-items-center">
                <img src="../assets/Gerb1.png" alt="" class="Logo">
                   <h5 class="text-light p-2 srt d-inline-block">Sirdaryo viloyati hokimligi</h5>
              </div>
                   
              
                   <img src="../assets/ITPARK.png" alt="" class=" Logo_IT">

        
           </div>


        </footer>
    </div>

</template>

<script>
export default {
    setup(){

        return {}
    }
}

</script>


<style >

.srt{
    width: 30%;
}
footer{
    width: 100%;
    height: 13vh;
    background-color: #01094F;
    display: flex;
}
ul{
    list-style: none;
    display: flex;
    color: white;
  
}
.link4{
    width: 5% !important;
}
.link5{
    width: 9% !important;
}
.link6{
    width: 7% !important;
}
.link7{
    width: 9% !important;
}
.link8{
    width: 10% !important;
}
.link8 i{
    display: block;
}
.link9{
    width: 8% !important;
}
.linkb{
 
   cursor: pointer;
}
.linkb:hover{
    color: #05E009;
}

.Logo_IT{
    width: 200px;
    height: 60px;
    position: fixed;
    right: 0;
}
.Logo{
    width: 100px;
    height: 100px;
    
   
}
.PS{
    position: fixed;
    right: 100px; 
}

</style>





