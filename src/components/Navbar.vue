<template>
<nav class="navbar bg">
  <a class="navbar-brand d-flex" href="#">
    <h2 class="navbar-brand text-dark font-weight-bold">Poke-Api</h2>
  </a>
      <img alt="Vue logo" src="../assets/poke.png" class="imagen">
  <div class="d-flex font">
  <router-link to="/" class="nav-link">Home</router-link> 
  </div>
</nav>
</template>

<style scoped>

  .bg{
    background-color: #dcdde1;
  }
  .imagen{
    width: 70px;
    height: 70px;
  }
  .nav-link{
    color: black;
    font-weight: 700;
  }
</style>