<template>
  <div id="app">
    

    <div class="container-fluid">
        <!-- Primera Fila -->
        
            <section-api>


            </section-api>
        </div>
      
    

    <!-- Footer    -->
    <page-footer></page-footer>

    <h1>{{ title }}</h1>
  </div>
</template>

<script>


import PageFooter from './components/PageFooter.vue';
import SectionApi from './components/SectionApi.vue';

export default {
  name: 'App',
  components:{
    PageFooter,
    SectionApi
  },
}
</script>

