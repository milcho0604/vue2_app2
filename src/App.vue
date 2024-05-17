<template>
  <div>
  <img alt="Vue logo" src="./assets/logo.png">
      <MyCheckbox3 />
    </div>
  </template>
  
  <script>
  import MyCheckbox3 from './MyCheckbox3.vue'
  
  export default {
    name: 'App',
    components: {
      MyCheckbox3
    }
  }
  </script>
  
  <style scoped>
  div { vertical-align: top; margin: 10px; }
  img { margin: 10px; }
  </style>
  