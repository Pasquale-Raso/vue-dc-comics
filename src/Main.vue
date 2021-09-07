<template>
  <main>
    <div class="main_box">
      <div class="container">
        <div class="oldcol">
          <div class="trecol">
            <div class="col1">
              <ul>
                <h3>DC COMICS</h3>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
                <h3>SHOP</h3>
                <li><a href="#">pasquale</a></li>
                <li><a href="#">pasquale</a></li>
              </ul>
              <div class="col2">
                <ul>
                  <h3>DC</h3>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                </ul>
              </div>
              <div class="col3">
                <ul>
                  <h3>SITES</h3>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
                  <li><a href="#">pasquale</a></li>
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
  color: white;
  position: relative;
}
.oldcol {
  display: flex;
}
.trecol {
  width: 400px;
}
.col1,
.col2,
.col3 {
  display: flex;
  padding-left: 50px;
}
img {
  width: 30%;
  height: 100%;
  position: absolute;
  right: 200px;
}
</style>