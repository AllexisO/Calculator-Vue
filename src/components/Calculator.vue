<template>
  <div class="calculator">
    <div class="display">00112233</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
    <div>Hello</div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.calculator{
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
</style>
