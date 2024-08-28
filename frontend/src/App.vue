<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome!! to Your Vue.js App" />
  <TestComponent></TestComponent>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import TestComponent from "@/components/TestComponent.vue";

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestComponent
  },
};

</script>

<style>
</style>
