<template>
  <header>
    <div class="container head">
      <img class="logo" src="@/assets/dc-logo.png" alt="logo" />
      <nav>
        <ul>
          <li v-for="link in links" :key="link.tex">
            <strong
              ><a href="#">{{ link.text }}</a></strong
            >
          </li>
        </ul>
      </nav>
    </div>
    <div class="sottotitolo">
      <h3><a class="content" href="#"> --> Content goes here --></a></h3>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<style scoped>
.head {
  background-color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  cursor: pointer;
}
nav {
  list-style-type: none;
}
ul li a {
  text-decoration: none;
  color: #1e2935;
  font-size: 11px;
}
li {
  display: inline-block;
  margin: 10px;
}
strong a:hover {
  color: #427abe;
  padding-bottom: 32px;
}
strong a:hover {
  color: #427abe;
  border-bottom: 4px solid #427abe;
}
img {
  width: 80px;
  margin-bottom: 10px;
}
.sottotitolo {
  height: 100px;
  background-color: black;
  color: white;
  display: flex;
  align-items: center;
}
.sottotitolo h3 {
  margin-left: 190px;
  font-size: 23px;
}
.content {
  color: white;
  text-decoration: none;
}
</style>