<template>
  <div class="layout-wrap">
    <canvas id="Keyvisual" class="keyviual-base"></canvas>
    <audio></audio>
    <button class="btn btn-volume">
      <span></span>
      <span></span>
      <span></span>
    </button>
    <button class="btn btn-play">PLAY</button>
  </div><!--/.layout-wrap-->
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  loading: true,
  created : function() {
    alert('break');

  }
}



</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
