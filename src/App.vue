<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MySecondoMain/>
  </div>
</template>

<script>
  import MyHeader from './components/MyHeader.vue'
  import MyMain from './components/MyMain.vue'
  import MySecondoMain from './components/MySecondoMain.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MySecondoMain
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  
}
* {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>
