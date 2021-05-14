<template>
  <div class="searchbar">
    <form>
        <input type="search" placeholder="Pesquisar sobre..." />
        <input type="button" value="Pesquisar">
    </form>
  </div>
</template>

<script>
export default {
  name: "SearchBar",
  props: {
    msg: String,
  },
};
</script>