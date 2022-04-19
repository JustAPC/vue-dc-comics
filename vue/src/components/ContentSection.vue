<template>
  <div id="content-menu">
    <div class="container">Content goes here</div>
  </div>
</template>

<script>
export default {
  name: "ContentSection",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
  color: white;
  font-weight: bold;
  font-size: 2em;
  padding: 35px 0;
}

#content-menu {
  background-color: #1c1c1c;
}
</style>
