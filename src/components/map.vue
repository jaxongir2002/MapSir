<script setup>
import Slider from '@vueform/slider'
import navbarVue from "./navbar.vue";
import footerVue from "./footer.vue";

import { ref } from "vue";
let value = ref(2022)
let active = ref(false);
let active3 = ref(false)

const isActive = ref(true);
const hasError = ref(false);
const toggleMenu = () => {
  active.value = !active.value;
};

let active2 = ref(false);

const isActive2 = ref(true);
const hasError2 = ref(false);
const toggleMenu1 = () => {
  active2.value = !active2.value;
};
const isActive3 = ref(true);
const hasError3 = ref(false);
const toggleMenu2 = () => {
  active3.value = !active3.value;
};



</script>

<template>
  <div class="position-relative">
    <navbarVue></navbarVue>

    <iframe src="https://yandex.uz/maps/-/CCUG7VgdwA" frameborder="0" class="w-100" style="height: 79vh"></iframe>

    <div class="left">
      <div class="ish2" @click="toggleMenu1()">
        <i class="fas fa-angle-double-right  text-white"></i>
      </div>
    </div>


    <div class="float-end right" @click="toggleMenu2()">
      <div >
        <i class="fas fa-angle-double-left text-white"></i>
      </div>
    </div>


<div :class="{ Big_box: active3 }">
  <div class=" container-fluid p-2"   v-if="active3">
      <div class="row m-auto" >
        <div class="box bg-success">
        </div>
        <div class="box blue">
        </div>
        <div class="box blue_1">
        </div>
        <div class="box blue_2">
        </div>
        <div class="box blue_3">
        </div>
        <div class="box pink">
        </div>
        <div class="box bg-danger">
        </div>
        <div class="box orenge">
        </div>
        <div class="box yellow">
        </div>
        <div class="box yellow_2">
        </div>
        <div class="box gold">
        </div>
      </div>
      <div class=" d-flex justify-content-between w-100">
        <span>1920</span>
        <span>1930</span>
        <span>1940</span>
        <span>1950</span>
        <span>1960</span>
        <span>1970</span>
        <span>1980</span>
        <span>1990</span>
        <span>2000</span>
        <span>2010</span>
        <span>2022</span>
      </div>
    </div>
</div>

    

  
    <div :class="{ silider2: active2 }">
      <p class=" text-light text-center">
2022 -
  </p>
  <v-range-slider
    v-model="value"
    direction="vertical"
    v-if="active2"
    color="#6fff00"
   
  ></v-range-slider>
  <p class=" text-light text-center">
  1920 -
  </p>
    </div>

    <footerVue></footerVue>
  </div>
</template>

<style  >
@import url('@vueform/slider/themes/default.css');

.right {
  background-color: red;
  position: absolute;
  right: 0;
  top: 180px;
  width: 30px;
  height: 400px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 20px 0px 0px 20px;
  background: linear-gradient(270deg, #533109 34.8%, rgba(0, 9, 87, 0) 91.94%);
  cursor: pointer;
}

span {
  font-size: large;
  color: white;

}

.Big_box {
  background-color: black;
  width: 50%;
  transform: rotateZ(-90deg);
  position: absolute;
  top: 430px;
  right: -380px;
 
}

.box {
  width: 80px;
  height: 50px;
  cursor: pointer;

}

.blue {
  background-color: rgb(0, 195, 255);
}

.blue_1 {
  background-color: #00B2FF;

}

.blue_2 {
  background-color: #0066FF;
}

.blue_3 {
  background-color: #001AFF;
}

.pink {
  background-color: #FF00B8;
}

.orenge {
  background-color: #FF7A00;
}

.yellow {
  background-color: #FF7A00;
}

.yellow_2 {
  background-color: #FFC700;
}

.gold {
  background-color: #FAFF00;
}




.left {
  width: 3%;
  position: absolute;
  z-index: 9999;
  top: 18%;


}

.ish2 {
  width: 40%;
  height: 60vh;
  background: linear-gradient(270deg, #003d0dbb 34.8%, rgba(0, 9, 87, 0) 91.94%);
  border-radius: 0px 15px 15px 0px;
  cursor: pointer;
  width: 30px;
  height: 400px;
  display: flex;
  align-items: center;
  justify-content: center;
}



.silider2 {
  width: 90px;
  height: 45vh;
  position: absolute;
  top: 18%;
  left: 3%;
  background: rgb(0, 0, 0);
 
}</style>
