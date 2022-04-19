<template>
  <div class="navbar-container">
    <div class="container">
      <ul class="py-5 d-flex justify-content-around align-items-center">
        <li v-for="(elm, i) in navbarList" :key="i">
          <img :src="elm.img" :alt="`${elm.name}`" />
          <a href="#">{{ elm.name }}</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data: function () {
    return {
      navbarList: [
        {
          name: "Digital Comics",
          img: "../assets/img/buy-comics-digital-comics.png",
        },
        {
          name: "DC Merchandise",
          img: "../assets/img/buy-comics-merchandise.png",
        },
        {
          name: "Subscription",
          img: "../assets/img/buy-comics-subscriptions.png",
        },
        {
          name: "Comic shop locator",
          img: "../assets/img/buy-comics-shop-locator.png",
        },
        {
          name: "DC Power visa",
          img: "../assets/img/buy-dc-power-visa.svg",
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
.navbar-container {
  background-color: #0282f9;
}

li {
  list-style-type: none;
}

li img {
  width: 20%;
}

a {
  text-decoration: none;
  color: white;
  padding-left: 20px;
  font-size: 0.9em;
}

a:hover {
  color: white;
  text-decoration: underline;
}
</style>
