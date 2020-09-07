<template>
  <div id="app">
    <header-top></header-top>
    <router-view></router-view>
    <footer-top></footer-top>
  </div>
</template>

<script>

import Header from './components/header'
import Footer from './components/footer'

export default {
  name: 'App',
  components: {
      'header-top': Header,
      'footer-top': Footer
  }
}
</script>

<style>

</style>
