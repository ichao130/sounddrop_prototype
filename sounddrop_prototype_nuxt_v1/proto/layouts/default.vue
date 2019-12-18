<template>
  <div id="Wrap" class="wrapper">
    <Header />
    <nuxt />
    <Footer />
  </div><!--/.wrapper-->
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Header, Footer
  },
  loading: true
}
</script>

<style>

</style>


