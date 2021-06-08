<template>
  <div class="searchbar">
    <form v-for="form in forms" :key="form">
      {{ forms.inputs }}
    </form>
  </div>
</template>

<script>
export default {
  name: "SearchBar",
  data() {
    return {
      forms: [
        { inputs: <input type="search" placeholder="Pesquisar sobre..." /> },
        { inputs: <input type="button" value="Pesquisar" /> },
      ],
    };
  },
};
</script>