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
