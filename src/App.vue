<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator/>

  </div>
</template>

<script>
import Calculator from './main/Calculator'
export default {
  components: { Calculator }
}
</script>

<style>

@font-face {
  font-family: "syne";
  src: url(./Fonts/SyneMono-Regular.ttf);
}
body {
  margin: 0;
  font-family: "syne";
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
 
 
  background-color: aquamarine;
}
</style>