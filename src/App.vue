<template>
  <div id="app">
    <!-- <seccion-menu></seccion-menu>  -->
    <seccion-banner></seccion-banner> 
    
  </div>
</template>

<script>

// import SeccionMenu from './components/SeccionMenu'

import SeccionBanner from './components/SeccionBanner.vue';

export default {
  name: 'App',
  components: {
    
    SeccionBanner,
    
    
  }
}
</script>