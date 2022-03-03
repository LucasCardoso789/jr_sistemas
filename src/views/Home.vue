<template>
  <div class="home">
    <div id="nav">
      <router-link to="/login">Login</router-link>
    </div>

    <div class="home_img">
      <img alt="Vue logo" src="../assets/logo.png">
    </div>
  </div>
</template>

<script>


</script>

<style>
    .home_img {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      width: 100vw;
    }

    #nav {
      padding: 30px;
    }
</style>
