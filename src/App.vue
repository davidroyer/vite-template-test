<template>
  <div class="canvas">
    <div class="border-8 border-black rounded-xl phone">phone</div>
  </div>
</template>

<script>
export default {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>

<style lang="postcss">
.canvas {
  @apply flex justify-center items-center;
}
.phone {
  width: 380px;
  height: 700px;

  @apply bg-gray-200;
}
</style>
