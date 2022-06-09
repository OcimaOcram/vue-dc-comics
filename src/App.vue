<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MySecondoMain/>
    <MyFooter/>
    <MySecondoFooter/>
  </div>
</template>

<script>
  import MyHeader from './components/MyHeader.vue'
  import MyMain from './components/MyMain.vue'
  import MySecondoMain from './components/MySecondoMain.vue'
  import MyFooter from './components/MyFooter.vue'
  import MySecondoFooter from './components/MySecondoFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MySecondoMain,
    MyFooter,
    MySecondoFooter
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
