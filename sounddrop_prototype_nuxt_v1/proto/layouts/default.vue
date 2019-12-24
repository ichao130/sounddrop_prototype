<template>
  <div id="Wrap" class="wrapper">
    <Header />
    <nuxt />
    <Footer />
    <About />
  </div><!--/.wrapper-->
</template>

<script>
import Header from '~/components/Header.vue'
import About from '~/components/About.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Header, Footer, About
  },
  loading: true
}
</script>

<style>

</style>