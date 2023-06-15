<template>
  <div class="home">
    <HelloWorld msg="Bienvenidos a Bluelock Fanpage"/>
    <img alt="bluelock" src="../assets/bluelock.jpeg">
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
