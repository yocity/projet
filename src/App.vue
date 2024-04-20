<template>
  <Index></Index>
</template>

<script>
import Index from './views/Index.vue'
export default {
  name: 'Home',
  components: {
    Index,
  },
}
</script>

<style>
  /*
    Ma palette de couleur est: 
    - #161925
    - #FFFFFF
    - #000000
   */
  body {
    display: flex;
    background-color: #fff;
    color: #161925;
  }
  #app{
    width: 100%;
    height: 100%;
    padding: 0;
    font-family: Poppins ,Verdana, Geneva, Tahoma, sans-serif;
  }
</style>