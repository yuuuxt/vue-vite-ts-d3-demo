<template>
  <h1>d3 sample</h1>
  <d3-chart></d3-chart>
</template>

<script lang="ts">
import {defineComponent} from 'vue'
import d3ChartSample from "./components/d3ChartSample.vue";
import d3Chart from "./components/d3Chart.vue";

export default defineComponent({
  name: 'App',
  components: {
    d3ChartSample, d3Chart
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 10px auto;
  max-width: 720px;
  padding-top: 10px;
}
</style>
