<template>
<!--  В данном хэдере существует навбар, с помощью которого производится роутинг в зависимости нужной нам страницы-->
  <b-navbar  class="border x  nav_color ">
    <div class="ml-5">
      <b-navbar-nav class="d-flex align-items-center">
        <b-nav-item class="d-flex justify-content-center align-items-center logo" :to="{name: 'main'}">
          <span class="nav__font2 logo__font">⛺️</span>
        </b-nav-item>
        <b-nav-item  :to="{name: 'add'}">
          <span class="nav__font">Создать резюме</span>
        </b-nav-item>
      </b-navbar-nav>
    </div>
  </b-navbar>
</template>


<style>
/* Header */
/* Navbar */
.nav_color{
  background: #d3c4c4;
  height: 80px;
}

.nav__font {
  font-weight: 400;
  font-size: 16px;
  color: rgb(7, 7, 7);
}
.nav__font:hover {
  color: #bd0808;
}
.nav__font2 {
  font-weight: 400;
  font-size: 16px;
  color: rgb(255, 255, 255);
}
.nav__font2:hover {
  color: #bd0808;
}

.logo {
  width: 50px;
  height: 50px;
  background: #281d41;
  border-radius: 50%;
}
.logo a{
  margin-bottom: 5px;
}
.logo__font {
  font-size: 25px;
}
</style>