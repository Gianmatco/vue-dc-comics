<template>
  <div id="app">
    <app-header/>
    <app-grid/>
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
  },
  data(){
    return{
      

    }
  }
}
</script>

<style scoped lang="scss">
@import './style/variables';
@import './style/generals';





</style>
