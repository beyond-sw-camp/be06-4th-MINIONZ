<template>
<<<<<<< Updated upstream
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome!! to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

=======
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <TestComponent></TestComponent>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import TestComponent from "@/components/TestComponent.vue";
>>>>>>> Stashed changes
export default {
  name: 'App',
  components: {
<<<<<<< Updated upstream
    HelloWorld
  }
}
=======
    HelloWorld,
    TestComponent
  },
};
>>>>>>> Stashed changes
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
