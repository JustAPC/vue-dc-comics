<template>
  <div id="app">
    <HeaderTop></HeaderTop>
    <ContentSection></ContentSection>
    <NavBar></NavBar>
    <FooterSection></FooterSection>
    <InfoSection></InfoSection>
  </div>
</template>

<script>
import "bootstrap";
import HeaderTop from "./components/HeaderTop.vue";
import ContentSection from "./components/ContentSection.vue";
import NavBar from "./components/NavBar.vue";
import FooterSection from "./components/FooterSection.vue";
import InfoSection from "./components/InfoSection.vue";
export default {
  name: "App",
  components: {
    HeaderTop,
    ContentSection,
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
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.container {
  padding: 0;
  width: 65%;
}
</style>
