<template>
  <div id="app">
    <app-header/>
    <main>
      <app-grid/>
    </main>
    <app-footer/>  
    
  </div>
</template>

<script>

import appHeader from './components/appHeader.vue'
import appGrid from './components/appGrid.vue'
import appFooter from './components/appFooter.vue'


export default {
  name: 'App',
  components: {
    appHeader,
    appGrid,
    appFooter
    
    
  }
}
</script>

<style scoped lang="scss">
@import './style/variables';
@import './style/generals';


</style>
