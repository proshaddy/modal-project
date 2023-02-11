<template>
  
  <h1>{{ title }}</h1>
  <div>
    <ModalApp :header="header" :text="text" theme="sale" />
  </div>
</template>

<script>
import ModalApp from './components/ModalApp.vue'
export default {
  name: 'App',
  components:{ ModalApp},
  data(){
    return {
      title:'My first vue App:)',
      header:'Sign up for the giveaway!',
      text:'Grag ur ninja swag for half price',
    }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
 h1 {
  border-bottom: 1px solid #ddd;
  display: inline-block;
  padding-bottom: 10px;

}

</style>
