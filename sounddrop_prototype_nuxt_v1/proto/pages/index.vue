<template>
  <div class="layout-wrap h100p font-inputmono_light">
    <canvas id="Keyvisual" class="keyviual-base"></canvas>
    <audio></audio>
    <button class="btn btn-volume">
      <span></span>
      <span></span>
      <span></span>
    </button>
    <div class="layout-box box-center">
    <button class="btn btn-play font-inputmono_light" v-on:click="play">{{ status }}</button>
    </div><!--/.play-area-->
    <div class="tuner-wrap font-inputmono_light">
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

  components: {},
  data: {
    status: 'Play'
  },
  loading: true,
  created : function() {
  },
  methods: {
    
    play: function() {
      status = 'Pause';


    }
  },
  watch: {
  }
}



</script>

<style>

</style>
