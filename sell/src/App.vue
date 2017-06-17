<template>
  <div id="app">
    <header></header>
    <div class="tab">
      i am a tab
    </div>
    <div class="content">
      content
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  import header from './components/header/header.vue';
  export default {
    components: {
      header: header
    }
  };
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
