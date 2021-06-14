<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ScreenCapture />
  </div>
</template>

<script>
// @ is an alias to /src
import ScreenCapture from '@/components/ScreenCapture.vue'

export default {
  name: 'Home',
  components: {
    ScreenCapture
  }
}
</script>
