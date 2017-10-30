<template>
  <div id="apps" style="width: 1600px">
 <heads ></heads >
    <router-view/>
  </div>
</template>

<script>
  import  heads from './components/head.vue'
export default {
  name: 'app',
  components:{heads}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
