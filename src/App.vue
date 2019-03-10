<template>
  <div id="app">
    <sub1  v-bind:products="products"/>
    <sub2  v-bind:products="products"/>
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
        products: [
            {name: 'Banana Skin', price: 20},
            {name: 'Shiny Star', price: 40},
            {name: 'Green Shells', price: 60},
            {name: 'Red Shells', price: 80}
        ]
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
