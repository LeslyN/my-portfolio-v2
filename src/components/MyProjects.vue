<template lang="pug">
  section#lesly-projects.section.projects
    .container
      h1.title.is-1.has-text-centered Projects
      .columns
        .column
          .card
            .card-image
              figure.image.is-4by3
                img.(src="/cardify-desktop.jpg" alt="Cardify desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img.(src="/cardify-mobile.jpg" alt="Cardify mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Materialize.
                br
                button
                  a(href="https://github.com/LeslyN/cardify/" target="_blank") Repositorio
                button
                  a(href="https://leslyn.github.io/cardify/public/index.html/" target="_blank") Demo
        .column
          .card
            .card-image
              figure.image.is-4by3
                img.(src="/labCar-desktop.jpg" alt="Labcar desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img.(src="/labCar-mobile.jpg" alt="Labcar mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Bootstrap.
                br
                button
                  a(href="https://github.com/LeslyN/lab-car-boilerplate/" target="_blank") Repositorio
                button
                  a(href="https://leslyn.github.io/lab-car-boilerplate/" target="_blank") Demo
        .column
          .card
            .card-image
              figure.image.is-4by3
                img.(src="/twitter-desktop.jpg" alt="Twitter desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img.(src="/twitter-mobile.jpg" alt="Twitter mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Bootstrap.
                br
                button
                  a(href="https://github.com/LeslyN/twitter/" target="_blank") Repositorio
                button
                  a(href="https://leslyn.github.io/twitter/" target="_blank") Demo
</template>

<style lang="stylus">
@import '../stylus/variables'
.projects
  background-color #F0F0F0
  h1.title
    margin-bottom 1.5em
  .service
    width 100%
    background white
    border-radius 4px
    padding 48px 20px
    box-shadow 0px 0px 10px rgba(0, 0, 0, 0.2)
    transition all 0.3s ease-in-out 0s
    &:hover
      box-shadow 0px 0px 30px rgba(0, 0, 0, 0.2)
    span.the-icon
      display block
      color primary-color
    h3
      margin-top 1.5em
      text-transform uppercase
</style>
