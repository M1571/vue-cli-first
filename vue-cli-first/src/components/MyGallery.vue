<template>
  <div class="gallery">
    <img v-for="(slide, index) in slides" src="../assets/logo.png" :key="index">
    
  </div>
</template>

<script>
export default {
  name: 'MyGallery',
  data() {
    return {
      slides: ["slide1", "slide2", "slide3"]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  border: 3px solid royalblue;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
