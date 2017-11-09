<template>
  <div id="apps" style="width: 1200px">
 <!--<heads ></heads >-->
    <!--<router-view/>-->
   <con></con>
  </div>

</template>

<script>
  import Vue from 'vue'
  import  heads from './components/head.vue'
  import  con from './components/content.vue'
  import Element from 'element-ui'
  Vue.use(Element)
export default {
  name: 'apps',
  components:{heads,con}
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
