<template lang="pug">
  #app
    Presentation
    AboutMe
    MyStack
    MyProjects
    Footer
</template>

<style lang="scss">
@import "~bulma/sass/utilities/initial-variables";
$family-primary: 'Quicksand', sans-serif;
@import "~bulma";
</style>

<style lang="stylus">
::selection
  background #dbdbdb;
::-moz-selection
  background #dbdbdb;
.button
  border-radius 100px
  padding 0.7em 1.5em
  box-shadow 0 10px 20px rgba(0, 0, 0, 0.2)
  font-weight 700
  line-height 1
  height auto
.vue-typer
  .custom
    &.caret
      background-color white
    &.char
      &.typed
        color white
      &.selected
        background rgba(219, 219, 219, 0.4)
        color: black
</style>


<script>
import AboutMe from './components/AboutMe';
import Presentation from './components/Presentation';
import Footer from './components/Footer';
import MyStack from './components/MyStack';
import MyProjects from './components/MyProjects';
export default {
  name: 'App',
  components: {
    Presentation,
    AboutMe,
    MyStack,
    MyProjects,
    Footer,
  },
};
</script>

