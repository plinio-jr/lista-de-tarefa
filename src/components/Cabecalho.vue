<template>
  <header>
    <h1>Atividade de Vue-Cli</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"],
};
</script>

<style>
header {
  background-color: red;
  color: black;
  height: 50px;
  width: 100%;
  display: flex ;
  align-items: center;
  justify-content: center;
}
</style>