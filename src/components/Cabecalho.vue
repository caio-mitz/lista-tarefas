<template>
  <header>
    <h1>{{ valor }}</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"],
};
</script>

<style>
header {
  background-color: royalblue;
  height: 50px;
  width: 100%;
  position: fixed;
  top: 0px;
  text-align: center;
  color: aliceblue;
}
</style>