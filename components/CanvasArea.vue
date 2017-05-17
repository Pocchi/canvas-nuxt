<template>
  <div class="CanvasArea">
    <canvas id="tutorial"></canvas>
  </div>
</template>
<script>
export default {
  name: 'CanvasArea',
  mounted: function () {
    console.log('created')
    this.$store.dispatch('createFunction')
  }
}
</script>
<style>
</style>
