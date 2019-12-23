<template>
  <div class="layout-wrap h100p">
    <canvas id="Keyvisual" class="keyviual-base"></canvas>
    <audio></audio>
    <button class="btn btn-volume">
      <span></span>
      <span></span>
      <span></span>
    </button>
    <div class="layout-box box-center">
    <button class="btn btn-play">PAUSE</button>
    </div><!--/.play-area-->
    <div class="tuner-wrap">
    <h2 class="hdl-title">Environmental Sound Tuner</h2>
    <div class="tuner-environmental_sound">
    <ul class="tuner-list">
      <li class="tuner-channel"><a href="#Park">Sound of Park</a></li>
      <li class="tuner-channel is-active"><a href="#Rain">Sound of Rain</a></li>
      <li class="tuner-channel"><a href="#Weather">Sound 0f Weather</a></li>
    </ul>
    </div><!--/.tuner-environmental_sound-->
    </div><!--/.tuner-wrap-->

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
