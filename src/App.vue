<template>
  <div id="app">
    <CounterUp />
  </div>
</template>

<script>
import CounterUp from "./components/CounterUp";

export default {
  name: "app",
  components: {
    CounterUp
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

#app {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

body {
  background-color: #f3f3f3;
}
</style>
