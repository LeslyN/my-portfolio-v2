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
            a(href="https://bulma.io/made-with-bulma/" target="blank")
              img.image-bulma(src="../assets/bulma.png")
            
</template>

<style lang="stylus">
.footer
  background black
  color white
  .rounded-link
    padding 0.5em
    background white
    color black
    border-radius 50%
    margin 0 0.5em
  p
    margin-top 20px

  .image-bulma 
    background-image url ('../assets/bulma.png')
    left 0
    padding 1em
    height 4em
    top 0
    width 9em
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

