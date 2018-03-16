<template lang="pug">
  section#lesly-projects.section.projects
    .container
      h1.title.is-1.has-text-centered Proyectos
      .columns
        .column
          .card
            .card-image
              figure.image.img-card
                //- img(src="../assets/cardify-desktop.jpg" alt="Cardify desktop")
                img(src="../assets/cardify-mobile.jpg" alt="Cardify mobile")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img(src="../assets/cardify-mobile.jpg" alt="Cardify mobile")
                .media-content
                  p.title.is-4.cardify-title Cardify
              .content En este proyecto se hace uso del framework Materialize.
                br
                a.button.is-primary.is-outlined(href="https://github.com/LeslyN/cardify/" target="_blank") Repositorio
                a.button.is-primary.is-outlined(href="https://leslyn.github.io/cardify/public/index.html/" target="_blank") Demo
        .column
          .card
            .card-image
              figure.image.is-4by3
                img(src="../assets/labcar-desktop.jpg" alt="Labcar desktop")
            .card-content
              .media
                .media-left
                  figure.image.is-48x48
                    img(src="../assets/labcar-mobile.jpg" alt="Labcar mobile")
                .media-content
                  p.title.is-4.cardify-title.lab-title Labcar
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
                  p.title.is-4.cardify-title.twitter-title Twitter
              .content En este proyecto se hace uso del framework Bootstrap.
                br
                a.button.is-primary.is-outlined(href="https://github.com/LeslyN/twitter/" target="_blank") Repositorio
                a.button.is-primary.is-outlined(href="https://leslyn.github.io/twitter/" target="_blank") Demo
</template>

<style lang="stylus">
@import '../stylus/svariables'
a.button.is-primary.is-outlined 
  margin: .5em 1em 0 0

.img-card
  background-image: url ('../assets/cardify-desktop.jpg')  
  background-position: center center 
  background-repeat: no-repeat
  background-size: cover 

.lab-title 
  color: #F7B617

.cardify-title 
  color: #EE6E73

.twitter-title 
  color: #2DAAE2
</style>