<template>
  <div id="vue-app">
    <ServiceRequestTracker />
  </div>
</template>

<script>
import ServiceRequestTracker from "./components/ServiceRequestTracker.vue";

export default {
  name: "app",
  components: {
    ServiceRequestTracker
  }
};
</script>

<style>
</style>
