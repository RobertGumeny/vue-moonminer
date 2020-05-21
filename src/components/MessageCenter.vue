<template>
  <div class="card messageCenter">
    <p>Message Center</p>
    <p class="mt-3">{{ message }}</p>
    <div class="d-flex justify-content-end">
      <button class="btn-sm text-small mr-2 mb-2">Clear</button>
    </div>
  </div>
</template>


<script>
export default {
  name: 'messageCenter',
  data() {
    return {
      message: "Check here for messages"
    }
  },
  computed: {},
  methods: {},
  components: {}
}
</script>


<style scoped>
.messageCenter {
  background-color: #000;
  border: 2px solid #8a8a8a;
  color: #fff;
}
</style>