<template>
  <div class="home container-fluid">
    <div class="row mb-5">
      <div class="col-12 text-center">
        <h1 class="display-4">Moon Miner</h1>
      </div>
    </div>
    <div class="row">
      <div class="col-5 mx-auto">
        <img src="../assets/moon-png.png" class="mb-3" />
        <MessageCenter />
      </div>
    </div>
  </div>
</template>

<script>
import MessageCenter from "../components/MessageCenter.vue"
export default {
  name: 'Home',
  components: {
    MessageCenter
  }
}
</script>

<style scoped>
.display-4 {
  color: #edc91a;
}
</style>
