<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import {mapState} from 'vuex'

export default {
  name: 'app',
  components: {

  },
  computed:{
    ...mapState(['userInfo'])
  }
}
</script>

<style scoped lang="stylus" ref="stylesheet/stylus">

</style>
