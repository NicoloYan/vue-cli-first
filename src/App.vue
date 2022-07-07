<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <PageTitle />
    <MyHero />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageTitle from './components/PageTitle.vue';
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    PageTitle,
    MyHero
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
