<template>
  <div id="app">
    <TitleComponent />
    <HeroImg />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TitleComponent from './components/TitleComponent.vue'
import HeroImg from './components/HeroImg.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TitleComponent,
    HeroImg,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img{width: 800px;}
</style>
