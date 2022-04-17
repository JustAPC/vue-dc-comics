<template>
  <div id="info-section">
    <div id="info-container" class="container d-flex justify-content-between align-items-center">
      <div>
        <a href="#">SIGN-UP NOW!</a>
      </div>

      <div class="d-flex">
        <h6>FOLLOW US</h6>
        <div class="icons">
          <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
          <a href="#"><i class="fa-brands fa-twitter"></i></a>
          <a href="#"><i class="fa-brands fa-youtube"></i></a>
          <a href="#"><i class="fa-brands fa-pinterest-p"></i></a>
          <a href="#"><i class="fa-solid fa-location-dot"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfoSection",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#info-section {
  background-color: #303030;
}

#info-container {
  padding: 35px 0;
}

div a {
  color: white;
  padding: 10px 13px;
  border: 2px solid #0282f9;
  font-size: 0.9em;
  font-weight: bold;
  text-decoration: none;
}

h6 {
  color: #0282f9;
  font-weight: bold;
  margin-right: 15px;
}

.icons a {
  color: #303030;
  padding: 5px 7px;
  margin: 0 7px;
  border-radius: 100%;
  border: 1px solid #797979;
  background-color: #797979;
}
</style>
