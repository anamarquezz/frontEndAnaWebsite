
<template>
  <div class="principal">
    <div class="div-izq">
      <div class="imgana">
      </div>
      <div class="links">
          <ul class="social-icons-list">
                <li><a href="https://github.com/anamarquezz" class="social-link" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
                <li><a href="https://www.linkedin.com/in/ana-marquez/" class="social-link" target="_blank"><i class="fab fa-linkedin"></i></a></li>
          </ul>
      </div>
    </div>
    <div class="div-der">
      <div class="black-block">
        <div>
          <p class="nombre">Ana Márquez</p>
          <p class="profession">Full Stack Developer</p>
        </div>
        <div class="img-viewmore">
          <div class="img-izq">
              <img class="img-illus" src="@/assets/img/img3.webp" alt="">
          </div>
          <div class="imf-der">
              <link rel="stylesheet" href="">
              <router-link to="/Dashboard"><i  class="iconviewmore fas fa-arrow-circle-right social-link"></i><p class="viewMore">View More</p></router-link>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}
</script>
<style>
    @import url('../assets/css/inicio.css');
</style>
