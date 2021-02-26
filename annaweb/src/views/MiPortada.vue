<template>
        <div class="back">
            <div class="main-background">
            <div class="child div-imagen">
            </div>
            <div class="child div-nombre">
                <div class="mi-nombre">
                    <p class="nombre">Ana Márquez</p>
                    <p class="position">Full Stack Developer</p>
                </div>
            </div>
            <div class="child div-viewmore">
                <ul class="links-icons">
                    <router-link to="/dashboard"><i class="fas fa-arrow-circle-right"></i></router-link>
                    <router-link class="text-link" to="/dashboard" ><p >View More</p></router-link>
                </ul>
            </div>
            <div class="child">
                <ul class="position-m">
                    <h3 class="">Full Stack Developer</h3>
                </ul>
                <ul class="div-contact">
                    <li><a href="https://github.com/anamarquezz" target="_blank"><i class="fab fa-github-square"></i></a></li>
                    <li><a href="https://www.linkedin.com/in/ana-marquez/" target="_blank" ><i class="fab fa-linkedin"></i></a></li>
                </ul>
                 <ul class="nombre-m">
                    <h3 class="">Ana Márquez</h3>
                </ul>
            </div>
            </div>
        </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {},
  data () {
    return {
      isMobile: false
    }
  },
  methods: {
  }
}
</script>
<style>
@import url('../assets/css/mi-portada.css');
</style>
