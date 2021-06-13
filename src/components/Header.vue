<template>
  <div>
    <div class="header">
      <h1>{{ initialMsg }}</h1>
      <h2>
        {{ topics }}
      </h2>
      <form action="searchbar">
        <input type="search" placeholder="Pesquisar sobre..." />
        <input type="button" value="Pesquisar" />
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      initialMsg: "Bem vindo ao Vue!",
      topics: "Topic 1 Topic 2 Topic 3 Topic 4",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
