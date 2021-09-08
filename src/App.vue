<template>
  <div id="app">
    <Header />
    <Banner />
    <Products />
    <NavbarIcons />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./Header.vue";
import NavbarIcons from "./NavbarIcons.vue";
import Main from "./Main.vue";
import Footer from "./Footer.vue";
import Banner from "./Banner.vue";
import Products from "./Products.vue";

export default {
  name: "App",
  components: {
    Header: Header,
    NavbarIcons: NavbarIcons,
    Main: Main,
    Footer: Footer,
    Banner: Banner,
    Products: Products,
  },
};
</script>

<style lang="css">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  max-width: 1000px;
  margin: 0 auto;
}
#app {
  font-family: "DM Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
