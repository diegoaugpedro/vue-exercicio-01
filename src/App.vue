<template>
  <div id="app">
    <Header />
    <Article :articles="articles" />
    <Topic :topics="topics" />
    <SearchBar />
    <NavBar />
    <SideBarImages />
    <SideBarSection />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Article from "./components/Article.vue";
import Topic from "./components/Topic.vue";
//import SearchBar from "./components/SearchBar.vue";
//import NavBar from "./components/NavBar.vue";
//import SideBarImages from "./components/SideBarImages.vue";
//import SideBarSection from "./components/SideBarSection.vue";

export default {
  name: "App",
  components: {
    Header,
    Article,
    Topic,
    //NavBar,
    //SideBarImages,
    //SideBarSection,
    //SearchBar,
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
