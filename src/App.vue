<template>
  <div class="main-container">
    <QRCode/>
  </div>
</template>

<script>
import QRCode from './components/QRCode.vue'

export default {
  name: 'App',
  components: {
    QRCode
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
}

#app {
  background-color: #D5E1EF;
}
</style>

<style scoped>
.main-container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
