<template>
  <div class="navbar">
    <div class="navbar-item" v-for="row in topics" :key="row">
      <tr>
        <td>
          <a :href="row.url" target="_blank" rel="noopener">Topic</a>
        </td>
      </tr>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  data() {
    return {
      topics: [
        { url: "https://pucminas.br"},
        { url: "https://take.net"},
        { url: "https://google.com.br"},
        { url: "https://cli.vuejs.org"},
      ]     
    };
  }
}
</script>