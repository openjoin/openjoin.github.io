<template>
  <img alt="Home Image" src="./assets/home.svg" height="250" />
  <HelloWorld msg="We believe Open Source is for everyone, yes you!" />
  <h2>OPEN SOURCE is NOT about code, it is about people and collaboration</h2>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
