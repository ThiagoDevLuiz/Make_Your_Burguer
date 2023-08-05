<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <Footer />
</template>

<script lang="ts">
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default ({
  name: 'App',
  components: {
    Navbar,
    Footer
  },
  data() {
    return {
      logo_src: '/img/logo.png',
      app_name: 'Make Your Burguer',
    }
  }
})
</script>

<style lang="scss">
  * {
    font-family: Helvetica;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .main-container {
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 2.62rem;
    margin-bottom: 30px;
    color: #222;
  }
</style>
