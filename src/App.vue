<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/layout/Header';

export default {
  name: "App",
  components: {
    Header
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  .btn {
    background: #555;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    padding: 7px 20px;
  }

  .btn:hover {
    background: #666;
  }

</style>
