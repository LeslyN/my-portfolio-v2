<template lang="pug">
  section#lesly-projects.section.projects
    .container
      h1.title.is-1.has-text-centered Proyectos
      .columns
        .column
          .card
            .card-image
              figure.image
                img(src="../assets/cardify-desktop.jpg" alt="Cardify desktop")
                //- img(src="../assets/cardify-mobile.jpg" alt="Cardify mobile")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img(src="../assets/cardify-mobile.jpg" alt="Cardify mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Materialize.
                br
                a.button.is-primary.is-outlined(href="https://github.com/LeslyN/cardify/" target="_blank") Repositorio
                a.button.is-primary.is-outlined(href="https://leslyn.github.io/cardify/public/index.html/" target="_blank") Demo
        .column
          .card
            .card-image
              figure.image.is-4by3
                img(src="../assets/labCar-desktop.jpg" alt="Labcar desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img(src="../assets/labCar-mobile.jpg" alt="Labcar mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Bootstrap.
                br
                a.button.is-primary.is-outlined(href="https://github.com/LeslyN/lab-car-boilerplate/" target="_blank") Repositorio
                a.button.is-primary.is-outlined(href="https://leslyn.github.io/lab-car-boilerplate/" target="_blank") Demo
        .column
          .card
            .card-image
              figure.image.is-4by3
                img(src="../assets/twitter-desktop.jpg" alt="Twitter desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img(src="../assets/twitter-mobile.jpg" alt="Twitter mobile")
                .media-content
                  p.title.is-4.cardify-title
              .content En este proyecto se hace uso del framework Bootstrap.
                br
                a.button.is-primary.is-outlined(href="https://github.com/LeslyN/twitter/" target="_blank") Repositorio
                a.button.is-primary.is-outlined(href="https://leslyn.github.io/twitter/" target="_blank") Demo
</template>

<style lang="stylus">
@import '../stylus/svariables'
a.button.is-primary.is-outlined 
  margin: .5em 1em 0 0

.lab-title 
  color:#F7B617

.cardify-title 
  color: #EE6E73

.twitter-title 
  color: #2DAAE2
</style>