<template>
  <header>
    <div class="headertop-container">
      <div class="container">
        <div class="d-flex justify-content-between align-items-center">
          <ul>
            <li>
              <a href="#"><img src="../assets/img/dc-logo.png" alt="" class="w-75" /></a>
            </li>
          </ul>

          <ul class="text-menu">
            <a href="#"><li>CHARACTERS</li></a>
            <a href="#"><li class="active">COMICS</li></a>
            <a href="#"><li>MOVIES</li></a>
            <a href="#"><li>TV</li></a>
            <a href="#"><li>GAMES</li></a>
            <a href="#"><li>COLLECTIBLES</li></a>
            <a href="#"><li>VIDEOS</li></a>
            <a href="#"><li>FANS</li></a>
            <a href="#"><li>NEWS</li></a>
            <a href="#"><li>SHOP</li></a>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderTop",

  methods: {
    activeMenu: function () {
      let item = document.querySelectorAll("li");
      if (item.classList.contains("active")) {
        item.classList.remove("active");
      } else {
        item.classList.add("active");
      }
    },
  },
};
</script>

<style scoped>
ul {
  padding: 0;
  margin: 0;
}

li {
  list-style-type: none;
  display: inline-block;
  font-weight: bold;
}

.text-menu li {
  padding: 50px 15px;
  font-size: 0.8em;
}

.text-menu a {
  text-decoration: none;
  color: #303030;
}

.headertop-container {
  background-color: white;
}

.active {
  color: #0282f9;
  border-bottom: 5px solid #0282f9;
}
</style>
