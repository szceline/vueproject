<template>
    <div id="app">
      <keep-alive>
        <router-view/>
      </keep-alive>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
  }
  </script>
<style scoped>
#app{  height:100%;}
#app div{ margin : auto;}
</style>