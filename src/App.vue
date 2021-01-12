<template>
  <div id="app">
    <Map />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Map from "./components/Map.vue";

@Component({
  components: {
    Map
  }
})
export default class App extends Vue {}
</script>


<style>

body, html {
  margin: 0;
  }

    #app {
      display: flex;
      flex-direction: column;
      height: 100vh;
      background-color: gray;
      }

</style>