<template>
  <div class="button-container">
    <button class="button">Was clicked:</button>
  </div>
</template>

<script>
export default {
  name: 'ButtonOne',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.button-container{
  display: flex;
  justify-content: center;
}

.button {
  width: 160px;
  height: 50px;
  border-radius: 10px;
  border: none;
  background-color: blue;
  color: white;
}
</style>
