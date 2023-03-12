<template>
  <div>
    <nav class=" ">
      <div class="container-fluid d-flex justify-content-between">
        <div class="logo gap-1">
          <img src="../assets/logo.png" alt="">
          <h4 class="text1 mt-3">Age<h4 class="text2 mt-3">Syrdarya
              <i class="fas fa-angle-down"></i>
            </h4>
          </h4>
          <div class="dropdown-content">
            <a href="#">Boyovut tumani
              Guliston shahar
              Guliston tumani
              Mirzaobod tumani
              Oqoltin tumani
              Sardoba tumani
              Sayxunobod tumani
              Shirin shahar
              Sirdaryo tumani
              Xovos tumani
              Yangiyer shahar </a>

          </div>
        </div>

        <div class="d-flex  w-50 justify-content-center gap-3 ">

          <ul class="linkbox d-flex mt-2 align-items-center">
            <li class="link1 link ">Loyiha haqida</li>
            <li class="link2 link">Infografika</li>
            <li class="link3 link">Biz bilan bog’lanish</li>

            <button class="knopka link">Uzb <i class="fas fa-angle-down"></i>
              <div class="dropdown1-content">
                <a href="#">Uzb </a>
                <a href="#">Ўзб</a>
                <a href="#">Рус </a>
                <a href="#">Eng </a>
              </div>
            </button>

          </ul>


          <div class="text-light gap-3 d-flex justify-content-around align-items-center">
            <lord-icon src="https://cdn.lordicon.com/msoeawqm.json" trigger="hover"
              colors="primary:#ffffff,secondary:#ffffff" style="width:40px;height:40px">
            </lord-icon>
            <i class="fab fa-instagram fs-3"></i>
            <i class="fab fa-facebook-f fs-3"></i>
          </div>
        </div>


      </div>
    </nav>
  </div>
</template>


<script>


</script>

<style>
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  top: 60px;
  height: 250px;
  width: 250px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 12;
  background-color: black;

}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  color: white;
  font-size: large;
  font-weight: bold;
  font-family: sans-serif;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.logo:hover .dropdown-content {
  display: block;
}


.dropdown1-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  top: 60px;
  height: 160px;
  width: 100px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 12;
  background-color: black;

}

.dropdown1-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  color: white;
  font-size: large;
  font-weight: bold;
  font-family: sans-serif;
}

.dropdown1-content a:hover {
  background-color: #ddd;
}





.knopka:hover .dropdown1-content {
  display: block;
}



nav {
  width: 100%;
  height: 7vh;
  background-color: #01094F;

}


.logo {
  width: 20%;
  height: 7vh;
  display: flex;
  align-items: center;
  cursor: pointer;
}

.text1 {
  display: inline-block;
  color: #FFE500;


}

.text2 {
  display: inline-block;
  color: white;

}

.linkbox {
  color: white;
  list-style: none;
}

.link {
  margin: 10px;
  font-size: large;
  font-weight: bold;
  font-family: 'Lucida Sans', ;
}

.knopka {
  border: none;
  background-color: #01094F;
  color: white;
  ;
}
</style>




