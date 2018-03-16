<template lang="pug">
  section#lesly-mystack.section
    .container
      h1.title.is-1.has-text-centered Lenguajes aprendidos
      .level
        .level-item
          .icon-container
            i.fab.fa-js-square.fa-fw.fa-4x
          h4.title.is-4 Javascript
        .level-item
          .icon-container
            i.fab.fa-html5.fa-4x
          h4.title.is-4 HTML5
        .level-item
          .icon-container
            i.fab.fa-css3-alt.fa-4x
          h4.title.is-4 CSS3
</template>

<style lang="stylus" scoped>
@import '../stylus/svariables'
.section
  h1.title
    margin-bottom 1em
.level-item
  flex-direction column
  .icon-container
    color primary-color
    margin-bottom 1.3em
</style>