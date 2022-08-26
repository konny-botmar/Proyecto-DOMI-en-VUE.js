<template>
  <div class="hello">
    <hr>
    <h1></h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
   div hr {
    color: white;
    margin-top: 0.2rem;
  } 
</style>
