<template lang="pug">
  nav.navbar.is-fixed-top(:class="{ 'is-scrolled': scrolled }")
    .navbar-brand
      a.navbar-item(href="/")
        img.logo(src="../assets/logoL.png")
      .navbar-burger.burger(@click="menuIsActive = !menuIsActive")
        span
        span
        span
    .navbar-menu(:class="{ 'is-active': menuIsActive }")
      .navbar-start
        a.navbar-item(href="#" v-scroll-to="'#lesly-presentation'") Inicio
        a.navbar-item(href="#" v-scroll-to="'#lesly-aboutme'") Acerca de mí
        a.navbar-item(href="#" v-scroll-to="'#lesly-mystack'") Skills
        a.navbar-item(href="#" v-scroll-to="'#lesly-projects'") Mis proyectos
      .navbar-end
        .navbar-item
          .field.is-grouped
            p.control
              a.button.is-primary(href="https://www.dropbox.com/s/4sqnz5c4pszznzl/CV_Nomberto-Coronado-2018.pdf?dl=0" target="_blank", :class="{ 'is-inverted is-outlined': !scrolled && !menuIsActive }")
                span.icon
                  i.fas.fa-download
                span Descarga CV
</template>

<style lang="stylus" scoped>
.navbar-menu.is-active
  a.navbar-item
    color black
a.navbar-item
  color white
  &:hover
    background-color transparent
    color white

.is-scrolled
  background white
  a.navbar-item
    color black

.logo 
  width 30% 
  max-height 100% 
  top 0
  left 0
</style>

<script>
export default {
  name: 'Header',
  data () {
    return {
      scrolled: false,
      menuIsActive: false
    }
  },
  methods: {
    handleScroll () {
      this.scrolled = window.scrollY > 0
    }
  },
  created () {
    window.addEventListener('scroll', this.handleScroll);
  },
  destroyed () {
    window.removeEventListener('scroll', this.handleScroll);
  },
};
</script>
