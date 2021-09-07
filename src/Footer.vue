<template>
  <footer>
    <div class="footer_box">
      <div class="container">
        <nav class="log">
          <div>
            <button><a href="#">SIGN-UP NOW!</a></button>
          </div>
          <ul class="log">
            <li>
              <h4><a href="#">FOLLOW US</a></h4>
            </li>
            <li>
              <img src="@/assets/footer-facebook.png" alt="facebook" />
            </li>
            <li>
              <img src="@/assets/footer-twitter.png" alt="twitter" />
            </li>
            <li>
              <img src="@/assets/footer-youtube.png" alt="youtube" />
            </li>
            <li>
              <img src="@/assets/footer-pinterest.png" alt="pinterest" />
            </li>
            <li>
              <img src="@/assets/footer-periscope.png" alt="periscope" />
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer_box {
  background-color: #30302f;
  color: white;
  z-index: 10;
  position: relative;
  height: 100px;
}
.log {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
li {
  display: inline-block;
  margin: 10px;
  margin-top: 10px;
  cursor: pointer;
}
img {
  width: 30px;
  margin-top: 30px;
}
button {
  margin-top: 25px;
  padding: 10px;
  background-color: #30302f;
  border: 2px solid #427abe;
}
h4 {
  margin-top: 25px;
}
button a {
  text-decoration: none;
  color: white;
}
a {
  text-decoration: none;
  color: #427abe;
}
</style>