<template>
  <div id="info-section">
    <div id="info-container" class="container d-flex justify-content-between align-items-center">
      <div>
        <a href="#" id="signup">SIGN-UP NOW!</a>
      </div>

      <div class="d-flex align-items-center">
        <h6>FOLLOW US</h6>
        <div class="icons">
          <a href="#" class="mx-2"><img src="../assets/img/footer-facebook.png" alt="" /></a>
          <a href="#" class="mx-2"><img src="../assets/img/footer-twitter.png" alt="" /></a>
          <a href="#" class="mx-2"><img src="../assets/img/footer-youtube.png" alt="" /></a>
          <a href="#" class="mx-2"><img src="../assets/img/footer-pinterest.png" alt="" /></a>
          <a href="#" class="mx-2"><img src="../assets/img/footer-periscope.png" alt="" /></a>
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

#signup {
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

.icons a img {
  width: 12%;
}
</style>
