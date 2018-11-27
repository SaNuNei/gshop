<template>
  <div id="app">
    <router-view/>
    <FootGuide/>
  </div>
</template>

<script>
import FootGuide from './components/FootGuide/FootGuide'
export default {
  components:{
    FootGuide
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus" type="text/stylus" scoped>

</style>
