<template lang="pug">
  section#lesly-mystack.section
    .container.background-skills
      h1.title.is-1.has-text-centered Skills
      .content
        h1.title.is-3.has-text-centered.has-text-weight-semibold Herramientas con las que trabajo
        .columns.is-multiline.is-mobile.is-centered.content-skill
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill 
            figure.image.is-128x128
              img(src="../assets/javascript.png", alt="Javascript")
              figcaption
                h3.is-3 Javascript
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/html5.png", alt="HTML5")
              figcaption
                h3.is-3 HTML5
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/jquery.png", alt="jQuery")
              figcaption
                h3.is-3 jQuery
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/css.png", alt="CSS3")
              figcaption
                h3.is-3 CSS3
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/ajax.png", alt="Ajax")
              figcaption
                h3.is-3 Ajax
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/git.png", alt="Git")
              figcaption
                h3.is-3 Git
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/reactjs.png", alt="React")
              figcaption
                h3.is-3 React
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/vue.png", alt="Vue")
              figcaption
                h3.is-3 Vue
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/angular.png", alt="Angular")
              figcaption
                h3.is-3 Angular
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/github.png", alt="Github")
              figcaption  
                h3.is-3 Github
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/photoshop.png", alt="Photoshop")
              figcaption
                h3.is-3 Photoshop
      
        h1.title.is-3.has-text-centered.has-text-weight-semibold Frameworks y Preprocesadores
        .columns.is-mobile.is-multiline.is-centered.content-skill
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/bootstrap.png", alt="Bootstrap")
              figcaption
                h3.is-3 Bootstrap
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/materialize.png", alt="Materialize")
              figcaption
                h3.is-3 Materialize
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/bulma-skills.png", alt="Bulma")
              figcaption
                h3.is-3 Bulma
          .column.is-gapless.is-one-quarter-desktop.is-one-third-tablet.is-half-mobile.content-item-skill
            figure.image.is-128x128
              img(src="../assets/pug.png", alt="Pug")
              figcaption
                h3.is-3 Pug/Jade
      
        h1.title.is-3.has-text-centered.has-text-weight-semibold Editores de texto
        .columns.columns-skill.is-multiline.is-mobile.content-skill.is-centered
          .column.is-gapless.is-one-quarter-desktop.is-half-tablet.is-half-mobile.content-item-skill.has-text-centered
            figure.image.is-128x128
              img(src="../assets/vscode.png", alt="Visual Studio Code")
            h3.is-3 Visual Studio Code
          .column.is-gapless.is-one-quarter-desktop.is-half-tablet.is-half-mobile.content-item-skill.has-text-centered
            figure.image.is-128x128
              img(src="../assets/brackets.png", alt="Brackets")
              figcaption
                h3.is-3 Brackets
</template>

<style lang="stylus" scoped>
@import '../stylus/svariables'
.section
  background-color #f6ece5

  h1.title
    margin-bottom 1em

  figure.image.is-128x128
    margin-left: auto;
    margin-right: auto;

  .content-skill
    margin-bottom 5em
    .content-item-skill
      margin 2em 0

  .level
    background-color #eed6bf
    padding 4em 16em
    max-width 100%

  .level-item
    flex-direction column
    .icon-container
      margin-bottom 1.3em
</style>