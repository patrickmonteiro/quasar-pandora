<template>
  <q-page class="container scene">
    <a-scene arjs='debugUIEnabled: false;'>
      <a-marker id='frac3' type='pattern' url='statics/marker/1.patt' vidhandler>
         <a-plane src="statics/caixa/1.jpeg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
        <a-entity camera></a-entity>
    </a-scene>

  </q-page>
</template>

<script>
export default {
  name: 'Aframe'
}
</script>

<style>
.scene {
    z-index: 100 !important;
}
</style>
