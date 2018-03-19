<template lang="pug">
  section#lesly-projects.section.projects
    .container
      h1.title.is-1.has-text-centered Proyectos
      .columns
        .column
          .service.has-text-centered
            img.image-card(src="../assets/cardify.png")
            .content
              h3.cardify-title.has-text-danger Cardify
              p
                | En este proyecto se hace uso del framework Materialize.
              .buttons.has-addons.is-centered
                .control
                  a.button.is-primary.is-outlined.is-rounded(href="https://github.com/LeslyN/cardify/" target="_blank") 
                    span.icon
                      i.fab.fa-github
                    span Código
                .control
                  a.button.is-primary.is-outlined(href="https://leslyn.github.io/cardify/public/index.html" target="_blank")
                    span.icon
                      i.fas.fa-eye
                    span Demo
        .column
          .service.has-text-centered
            img.image-card(src="../assets/labcar.png")
            .content
              h3.lab-title.has-text-warning LabCar
              p
                | En este proyecto se hace uso del framework Bootstrap.
              .buttons.has-addons.is-centered
                .control
                  a.button.is-primary.is-outlined(href="https://github.com/LeslyN/lab-car-boilerplate" target="_blank")
                    span.icon
                      i.fab.fa-github
                    span Código
                .control
                  a.button.is-primary.is-outlined(href="https://leslyn.github.io/lab-car-boilerplate/" target="_blank")
                    span.icon
                      i.fas.fa-eye
                    span Demo
        .column
          .service.has-text-centered
            img.image-card(src="../assets/twitter.png")
            .content
              h3.twitter-title.has-text-info Twitter
              p
                | En este proyecto se hace uso del framework Bootstrap.
              .buttons.has-addons.is-centered
                .control
                  a.button.is-primary.is-outlined(href="https://github.com/LeslyN/twitter" target="_blank")
                    span.icon
                      i.fab.fa-github
                    span C&oacute;digo
                .control
                  a.button.is-primary.is-outlined(href="https://leslyn.github.io/twitter/" target="_blank")
                    span.icon
                      i.fas.fa-eye
                    span Demo
        
</template>

<style lang="stylus">
@import '../stylus/svariables'

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

    h3
      margin-top 1.5em
      text-transform uppercase


    a.button.is-primary.is-outlined 
      margin .5em 1em 0 0

    .image-card 
      width 100% 
      height auto 
      top 0
      left 0

</style>