<template>
  <div id="app">
    <h1>QRコード生成</h1>
    <qr-code-generator/>
  </div>
</template>

<script>
import QrCodeGenerator from "./components/QRCodeGenerator.vue";

export default {
  name: "app",
  components: {
    QrCodeGenerator
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
