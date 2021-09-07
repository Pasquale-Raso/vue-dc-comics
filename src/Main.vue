<template>
  <main>
    <div class="main_box">
      <div class="container">
        <div class="oldcol">
          <div class="trecol">
            <div class="col1">
              <ul>
                <h4>DC COMICS</h4>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
                <h4>SHOP</h4>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
              </ul>
              <div class="col2">
                <ul>
                  <h4>DC</h4>
                  <li><a href="#">Terms Of Use</a></li>
                  <li><a href="#">Privacy policy (New)</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificates</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
                </ul>
              </div>
              <div class="col3">
                <ul>
                  <h4>SITES</h4>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power Visa</a></li>
                </ul>
              </div>
            </div>
          </div>
          <img src="@/assets/dc-logo-bg.png" alt="logo" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped>
.main_box {
  height: 400px;
  background-color: black;
  background-image: url(./assets/footer-bg.jpg);
  color: white;
  position: relative;
}
.oldcol {
  display: flex;
}
.trecol {
  width: 400px;
  margin-top: 20px;
}
.col1,
.col2,
.col3 {
  display: flex;
  padding-left: 40px;
}
img {
  height: 140%;
  position: absolute;
  right: 160px;
  top: -70px;
}
a {
  text-decoration: none;
  color: #999ca1;
  font-size: 10px;
}
ul {
  list-style-type: none;
}
h4 {
  margin-top: 15px;
}
</style>