<template>
  <div id="app">
    <Navbar />
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style>
.center-fluid {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.center {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
