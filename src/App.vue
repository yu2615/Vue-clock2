<template>
  <Clock />
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Clock from './components/ClockScreen.vue';

export default {
  name: 'App',
  components: {
    Clock,
  }
}
</script>

<style>
html,
body{
  height: 100%;
  margin: unset;
}
#app {
 height: 100%;
}
</style>
