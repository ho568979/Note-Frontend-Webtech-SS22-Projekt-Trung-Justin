<template>
  <body>
    <div class="home">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
      <i class="fas fa-book-open logo"></i>
      <HelloWorld></HelloWorld>
      <router-link class="btn" to="/account"><i class="fas fa-chevron-right"></i>Anmelden</router-link>
    </div>
  </body>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
  /*Logo*/
  .fa-book-open, logo{
    font-size: 120px;
    color: #0d6efd;
  }
</style>
