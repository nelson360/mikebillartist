<template>
  
  <img alt="Vue logo" src="/pictures/mikeBill3.png" class="firstimage">
 
  <HeaderComponent/>
  <BodyComponent/>
  <FooterComponent/>
</template>

<script>

import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import BodyComponent from './components/BodyComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent, BodyComponent, FooterComponent
  }
}
</script>

<style>

.firstimage{
  float:left;
  width:100px;
  margin:0 10px;
}

</style>
