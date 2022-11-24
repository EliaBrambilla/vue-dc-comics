<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent :data="cardsDCComics"/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import {cardsDCComics} from '@/data'
export default {
  name: 'App',
    data(){
      return{
        cardsDCComics
      };
    },
    
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
    
}
}
</script>

<style lang="scss">
  $zero-auto: 0 auto;
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>