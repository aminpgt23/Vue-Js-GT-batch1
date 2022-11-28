<template>
  <div id="app">
    <Navbar></Navbar>
    <breadcrumbs></breadcrumbs>
    <gallery></gallery>
    <slider></slider>
    <fouter></fouter>
    <copyright></copyright>
  </div>
</template>

<script>

import fouter from './components/fouter.vue'
import Navbar from './components/Navbar.vue'
import breadcrumbs from './components/breadcrumbs.vue'
import gallery from './components/gallery.vue'
import slider from './components/slider.vue'
import copyright from './components/copyright.vue'

export default {
  name: 'App',
  components: {
   Navbar,
   breadcrumbs,
   gallery,
   slider,
   fouter,
   copyright
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 0px; */
}
</style>
