<template>
  <div class="hero-bg">
    <div class="container d-flex">
      <div class="d-flex w-50 pb-4">
        <div class="footer-menu py-5">
          <h6>DC COMICS</h6>
          <ul class="py-3">
            <a href=""><li>Characters</li></a>
            <a href=""><li>Comics</li></a>
            <a href=""><li>Movies</li></a>
            <a href=""><li>Tv</li></a>
            <a href=""><li>Games</li></a>
            <a href=""><li>Videos</li></a>
            <a href=""><li>News</li></a>
          </ul>

          <h6 class="pb-3">SHOP</h6>
          <ul>
            <a href=""><li>Shop DC</li></a>
            <a href=""><li>Shop DC Collectibles</li></a>
          </ul>
        </div>

        <div class="footer-menu py-5">
          <h6>DC</h6>
          <ul class="py-3">
            <a href=""><li>Terms Of Use</li></a>
            <a href=""><li>Privacy Policy (News)</li></a>
            <a href=""><li>Ad Choices</li></a>
            <a href=""><li>Advertising</li></a>
            <a href=""><li>Jobs</li></a>
            <a href=""><li>Subscriptions</li></a>
            <a href=""><li>Talent Workshops</li></a>
            <a href=""><li>CPSC Certificates</li></a>
            <a href=""><li>Ratings</li></a>
            <a href=""><li>Shop Help</li></a>
            <a href=""><li>Contact Us</li></a>
          </ul>
        </div>

        <div class="footer-menu py-5">
          <h6>SITES</h6>
          <ul class="py-3">
            <a href=""><li>DC</li></a>
            <a href=""><li>MAD Magazine</li></a>
            <a href=""><li>DC Kids</li></a>
            <a href=""><li>DC Universe</li></a>
            <a href=""><li>DC Power Visa</li></a>
          </ul>
        </div>
      </div>

      <div class="align-items-stretch img-container dc-logo-bg"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterSection",
  data: function () {
    return {
      dcComicsList: [
        {
          name: "Characters",
          url: "#",
        },
        {
          name: "Comics",
          url: "#",
        },
        {
          name: "Movies",
          url: "#",
        },
        {
          name: "TV",
          url: "#",
        },
        {
          name: "Games",
          url: "#",
        },
        {
          name: "Videos",
          url: "#",
        },
        {
          name: "News",
          url: "#",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.hero-bg {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

li {
  list-style-type: none;
  color: grey;
  font-size: 0.7em;
}

p {
  color: white;
}

div {
  color: white;
}

.footer-menu {
  width: 25%;
}

h6 {
  font-weight: bold;
}

a {
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
  color: white;
}

.img-container {
  width: 40%;
  margin-left: 100px;
}

.dc-logo-bg {
  background-image: url(../assets/img/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
</style>
