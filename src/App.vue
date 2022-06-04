<template>
  <div id="app">
    <div class="container">
        <base-header/>
    </div>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import BaseMain from './components/BaseMain.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';

</style>
