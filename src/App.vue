<template>
  <img alt="" src="">
    <HeaderIndex/>
    <video-introductory/>
    <all-categories/>
    <FooterIndex/>
</template>

<script>
import HeaderIndex from './components/HeaderIndex.vue'
import VideoIntroductory from './components/VideoIntroductory.vue'
import FooterIndex from './components/FooterIndex.vue'
import AllCategories from './components/AllCategories.vue'


export default {
  name: 'App',
  components: {
    HeaderIndex,
    VideoIntroductory,
    AllCategories,
    FooterIndex,
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
