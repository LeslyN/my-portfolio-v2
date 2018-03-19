<template lang="pug">
  section#lesly-projects.section.projects
    .container
      h1.title.is-1.has-text-centered Proyectos
      .columns
        .column
          .service.has-text-centered
            figure
              img.image-card(src="../assets/cardify.jpg")
            .content
              h3.cardify-title Cardify
              p
                | En este proyecto se hace uso del framework Materialize.
              br
              a.button.is-primary.is-outlined(href="https://github.com/LeslyN/cardify/" target="_blank") Repositorio
              a.button.is-primary.is-outlined(href="https://leslyn.github.io/cardify/public/index.html" target="_blank") Demo
        
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
      position absolute
      top 0
      left 0

    .lab-title 
      color #F7B617

    .cardify-title 
      color #EE6E73

    .twitter-title 
      color #2DAAE2
</style>