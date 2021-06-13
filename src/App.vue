<template>
  <div id="app">
    <Header />
    <Article />
    <NavBar />
    <SideBarSection />
    <SideBarImages />
    <tr class="imageItems" v-for="img in imageItems" :key="img">
      <td>
        <img :src=imageItems />
      </td>
    </tr>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Article from "./components/Article.vue";
import NavBar from "./components/NavBar.vue";
import SideBarSection from "./components/SideBarSection.vue";
//import SideBarImages from "./components/SideBarImages.vue";
import Batman from "./images/B1.png";
import Superman from "./images/S1.png";
import MulherMaravilha from "./images/M1.jpg";

export default {
  name: "App",
  components: {
    Header,
    Article,
    NavBar,
    SideBarSection,
    //SideBarImages,
  },
  data() {
    return {
      imageItems: [{ src: Batman }, { src: Superman }, { src: MulherMaravilha }],
    };
  },
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
