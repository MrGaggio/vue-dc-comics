<template>
  <div id="app">
    <Header />
    <Main />
    <Cards />
    <Footer />
    
  </div>
</template>

<script>
  import Header from "./components/Header.vue"
  import Main from "./components/Main.vue"
  import Footer from "./components/Footer.vue"
  import Cards from "./components/Cards.vue"

  export default {
    name: 'App',
    components: {
      Header,
      Main,
      Cards,
      Footer,
      
    }
  }
</script>

<style lang="scss"></style>
