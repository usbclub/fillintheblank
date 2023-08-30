<template>
  <Hello />
</template>

<script>
import Hello from "./components/Hello.vue";
export default {
  name: "App",
  components: {
    Hello,
  },
};
</script>

<style>
body,
html {
  height: 100%;
  background: #BDC0B6;
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
}
</style>
