<template>
  <img alt="" src="">
    <HeaderIndex/>

</template>

<script>
import HeaderIndex from './components/HeaderIndex.vue'

export default {
  name: 'App',
  components: {
    HeaderIndex
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html{
    font-size: 62.5%;
}

body{
    margin-top: 0px;
    padding: 0px;
    font-size: 13px;
    font-family: Arial, Helvetica, sans-serif;
}
</style>
