<template>
  <div id="app">

    <nav>
      <img class="logo-principal" src="../src/assets/Intec_logo.png">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> | -->
      
      <!-- <router-link to="/appointments">Appointments</router-link> -->
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app{
  width: 100%;
  height: 100%;
}
nav {
  padding: 30px;
}
/* 
.logo-principal{
  display: flex;
  margin: auto;
} */

</style>
