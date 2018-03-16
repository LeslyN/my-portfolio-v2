<template lang="pug">
  #lesly-presentation.section.hero.is-fullheight.first-section
    Header
    .hero-body
      .overlay
      .container.has-text-centered
        h3.title.is-3 Hola, mi nombre es
        h1.title.is-name Lesly Nomberto 
        .is-hidden-touch
          h2.title.is-2
            span soy 
            vue-typer(:text=[
              'Front-end Developer.',
              'Alegre.',
            ])
        .is-hidden-desktop
          h3.title.is-3.text-change-mobile
            span.span-first-text soy
            vue-typer(:text=[
              'Front-end Developer.',
              'Alegre.'])
</template>

<style lang="stylus">
@import "../stylus/media-queries"
.first-section
  background url("../assets/image-header.jpg") center no-repeat
  background-size cover
  .overlay
    position absolute
    top 0
    left 0
    height 100%
    width 100%
    background-color #000000
    opacity 0.4
  .text-change-mobile
    .span-first-text
      display block
  h1, h3, h2
    color white
  .is-name
    font-size 80px
    letter-spacing 10px
    +mobile()
      font-size 60px
</style>

<script>
import { VueTyper } from 'vue-typer';
import Header from './Header';
export default {
  name: 'Presentation',
  components: {
    Header,
    VueTyper,
  },
};
</script>