<template>
  <div>
    <Header />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header/Header.vue";
import Footer from "../components/Footer/Footer.vue";

export default {
  name: "MainView",
  components: {
    Header: Header,
    Footer: Footer
  }
};
</script>

<style></style>
