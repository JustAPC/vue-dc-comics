<template>
  <div id="app">
    <HeaderTop></HeaderTop>
    <HeaderMid></HeaderMid>
    <NavBar></NavBar>
    <FooterSection></FooterSection>
    <InfoSection></InfoSection>
  </div>
</template>

<script>
import HeaderTop from "./components/HeaderTop.vue";
import HeaderMid from "./components/HeaderMid.vue";
import NavBar from "./components/NavBar.vue";
import FooterSection from "./components/FooterSection.vue";
import InfoSection from "./components/InfoSection.vue";
export default {
  name: "App",
  components: {
    HeaderTop,
    HeaderMid,
    NavBar,
    FooterSection,
    InfoSection,
  },
};
</script>

<style lang="scss">
@import "bootstrap/dist/css/bootstrap.min.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 20px;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.container {
  padding: 0;
}
</style>
