<template>
  <div class="bannerbg">
    <button><a href="#">CURRENT SERIES</a></button>
  </div>
</template>

<script>
export default {
  name: "Banner",
  data() {
    return {};
  },
};
</script>

<style scoped>
.bannerbg {
  background: url(./assets/jumbotron.jpg) no-repeat center;
  background-size: 100%;
  background-position: top;
  width: 100%;
  height: 300px;
}
button {
  margin-top: 280px;
  margin-left: 210px;
  padding: 10px;
  background-color: #427abe;
  border: 0px;
  font-size: 20px;
}
a {
  color: white;
  text-decoration: none;
}
</style>