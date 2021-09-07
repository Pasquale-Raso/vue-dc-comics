<template>
  <footer>
    <div class="footer_box">
      <div class="container">
        <nav class="log">
          <div>
            <button>SIGN-UP NOW!</button>
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
}
.log {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
li {
  display: inline-block;
  margin: 10px;
}
img {
  width: 30px;
}
strong {
  margin-bottom: 30px;
}
</style>