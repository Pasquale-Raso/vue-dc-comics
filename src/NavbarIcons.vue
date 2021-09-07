<template>
  <div class="navbar_blu_line">
    <div class="container">
      <ul>
        <li v-for="icon in icons" :key="icon">
          <img :src="icon.image" />
          <p>{{ icon.text }}</p>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarIcons",
  data() {
    return {
      icons: [
        {
          text: "DIGITAL COMICS",
          image: require("@/assets/buy-comics-digital-comics.png"),
        },
        {
          text: "DC MERCHANDISE",
          image: require("@/assets/buy-comics-merchandise.png"),
        },
        {
          text: "SUBSCRIPTIONS",
          image: require("@/assets/buy-comics-subscriptions.png"),
        },
        {
          text: "COMIC SHOP LOCATOR",
          image: require("@/assets/buy-comics-shop-locator.png"),
        },
        {
          text: "DC POWER VISA",
          image: require("@/assets/buy-dc-power-visa.svg"),
        },
      ],
    };
  },
};
</script>

<style scoped>
.navbar_blu_line {
  height: 130px;
  background-color: #427abe;
  color: white;
  display: flex;
  align-items: center;
  z-index: 8;
  position: relative;
}
li {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 30px;
  cursor: pointer;
}
ul {
  display: flex;
}
img {
  width: 30px;
}
p {
  font-size: 11px;
  padding: 8px;
}
</style>