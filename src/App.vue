<template>
  <!-- <Header /> -->
  <div class="container">
    <router-view></router-view>
  </div>
</template>
  
  <script>
  import Header from './components/header.vue'
  export default {
      name: 'App',
      components: {
          Header,
      }
  }
  </script>