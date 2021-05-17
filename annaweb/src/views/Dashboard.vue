<template>
  <div id="Dashboard" class="back">
    <div class="d-menu-izq">
      <div class="Image-name">
        <div class="img-div">
          <img width="130" src="@/assets/img/img3.webp" alt="">
        </div>
        <p class="name">Ana Márquez</p>
        <p class="position">Full Stack Developer</p>
      </div>
      <div class="d-nav-bar">
        <ul class="list-menu">
          <li class="active"><a href="#">INIT</a></li>
          <li><a href="#">Projects</a></li>
          <li><a href="#">Tutorials</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </div>
    </div>
    <div class="d-title-projects-cards">
      <div class="titlee">
        <p>Projects</p>
      </div>
      <div class="icons-title">
        <ul>                 
            <li><a href="#"><i class="fas fa-search"></i></a></li>
            <li><a href="#"><i class="fas fa-chevron-circle-left"></i></a></li>
            <li><a href="#"><i class="fas fa-sync-alt"></i></a></li>
            <li><a href="#"><i class="fas fa-chevron-circle-right"></i></a></li>
        </ul>           
      </div>    
    </div>
    <div class="d-projects-cards">
      <cardRoundtop v-for="n in 12" v-bind:key="n"></cardRoundtop>
    </div>
  </div>
</template>
<script>
  // @ is an alias to /src
  import cardRoundtop from '@/components/cardRoundtop.vue'

  export default {
    name: 'Dashboard',
    components: {
      cardRoundtop
    }
  }

</script>
<style>
  @import url('../assets/css/dashboard.css');

</style>
