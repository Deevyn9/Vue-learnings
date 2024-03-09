<template>
  <div class="main-app">
    <Navbar />
    <MainPage />
  </div>
</template>

<script>
import Navbar from "./components/NavBar.vue";
import MainPage from "./components/MainPage.vue";

export default {
  components: {
    Navbar,
    MainPage
  },
}
</script>