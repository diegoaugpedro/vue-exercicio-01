<template>
  <div id="app">
    <Header msg= "Framework Front End - Vue"/>
    <Topic />
    <SearchBar />
    <NavBar />
    <SideBarImages />
    <Article />
    <SideBarSection />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Topic from './components/Topic.vue'
import SearchBar from './components/SearchBar.vue'
import NavBar from './components/NavBar.vue'
import SideBarImages from './components/SideBarImages.vue'
import Article from './components/Article.vue'
import SideBarSection from './components/SideBarSection.vue'


export default {
  name: 'App',
  components: {
    Header, Topic, NavBar, SideBarImages, Article, SideBarSection, SearchBar
  }
}
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
