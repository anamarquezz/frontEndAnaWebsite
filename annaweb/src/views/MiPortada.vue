<template>
    <div class="principal">
        <div id="main-background">
            <div class="c-izq">
                <img src="@/assets/img/img3.webp" alt="https://society6.com/annamachtart" title="https://society6.com/annamachtart" class="anchor-tooltip">
                <ul class="social-icons">
                    <li><a href="https://github.com/anamarquezz" target="_blank"><i class="fab fa-github-square"></i></a></li>
                    <li><a href="https://www.linkedin.com/in/ana-marquez/" target="_blank" ><i class="fab fa-linkedin"></i></a></li>
                </ul>
            </div>
            <div class="c-der">
                <div class="mi-nombre">
                    <p class="nombre">Ana Márquez</p>
                    <p class="position">Full Stack Developer</p>
                </div>
                <div class="go-site">
                    <ul>
                        <router-link to="/dashboard"><i class="fas fa-arrow-circle-right"></i></router-link>
                        <router-link to="/dashboard" ><p class="text-link">More Info</p></router-link>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {}
}
</script>
<style>
@import url('../assets/css/mi-portada.css');
</style>
