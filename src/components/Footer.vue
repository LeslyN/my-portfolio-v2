<template lang="pug">
  .footer
    .container
      .content.has-text-centered
        a.rounded-link(href="#") 
          i.far.fa-envelope
        a.rounded-link(href="https://www.linkedin.com/in/leslynomberto/" target="_blank")
          i.fab.fa-linkedin-in.fa-fw
        a.rounded-link(href="https://www.github.com/LeslyN/" target="_blank")
          i.fab.fa-github.fa-fw
        p
          span lnombertoc@gmail.com 
          span &copy
          span {{ ` ${actualDate}` }}
          br
          span 
            img.image-bulma.has-text-centered(src="../assets/made-with-bulma.png")
</template>

<style lang="stylus">
.footer
  background black
  color: white
  .rounded-link
    padding 0.5em
    background white
    color black
    border-radius 50%
    margin 0 0.5em
  p
    margin-top 20px

  .image-bulma 
    padding: 1em
    width: 9em
    height: 4em
</style>

<script>
export default {
  data () {
    return {
      actualDate: null
    }
  },
  mounted () {
    const actualDate = new Date()
    this.actualDate = actualDate.getFullYear()
  }
}
</script>

