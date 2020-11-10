<template>
  <div id="app">
        <the-header/>


    <router-view/>
  </div>
</template>
<script>
  import theHeader from "./components/home/header.vue";
  export default {
    components:{
      // eslint-disable-next-line vue/no-unused-components
      theHeader
    }
  }
</script>
<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
  </style>
