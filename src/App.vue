<template>
  <div id="app">
    <sub1/>
    <sub2/>
  </div>
</template>

<script>
import subOne from './components/subOne.vue';
import subTwo from './components/subTwo.vue';

export default {
  name: 'App',
  components: {
    'sub1': subOne,
    'sub2': subTwo
  },
  data () {
    return {

    }
  }

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 50%;
  margin: auto;
}
</style>
