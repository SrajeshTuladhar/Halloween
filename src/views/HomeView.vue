<template>
  <div class="home">
    <img alt="Halloween logo" src="../assets/logo.png" width="800" height="500">
    <HelloWorld msg="October 31, 2022"/>
  </div>
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
