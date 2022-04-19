<template>
  <li class="col-2 pb-4">
    <div class="card-bg" :style="{ backgroundImage: 'url(' + thumb + ')' }"></div>
    <p class="pt-3 description">{{ series }}</p>
  </li>
</template>

<script>
export default {
  name: "ComicsCard",
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
};
</script>

<style>
li {
  list-style-type: none;
  display: inline-block;
}

.card-bg {
  height: 160px;
  width: 160px;
  background-size: cover;
}

.description {
  font-size: 0.8em;
  color: white;
  text-transform: uppercase;
}
</style>
