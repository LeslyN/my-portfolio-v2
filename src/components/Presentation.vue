<template lang="pug">
  #lesly-presentation.section.hero.is-fullheight.first-section
    Header
    .hero-body
      .overlay
      .container.has-text-centered
        h3.title.is-3 Hola, mi nombre es
        h1.title.is-name Lesly Nomberto
        h3.title.is-4 Front-end Developer
        .is-hidden-touch
          h2.title.is-2
            span and I build&nbsp;
            vue-typer(:text=[
              'user interfaces.',
              'landing pages.',
              'corporate websites.',
              'web applications.'])
        .is-hidden-desktop
          h3.title.is-3.text-change-mobile
            span.span-first-text and I build
            vue-typer(:text=[
              'user interfaces.',
              'landing pages.',
              'corporate websites.',
              'web applications.'])
</template>

<script>
import { VueTyper } from 'vue-typer'
import Header from './Header'
export default {
  name: 'Presentation',
  components: {
    Header,
    VueTyper
  }
}
</script>
