<template>
<body>
 <div id="display">
  <img class="display" src="../assets/background.jpg" alt="">
 </div>
</body>
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
<style>
.display {
  background-repeat: no-repeat;
  background-size: cover;
  width: 100vw;
  height: 90vh;
}
</style>
