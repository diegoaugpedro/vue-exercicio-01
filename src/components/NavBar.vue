<template>
  <div class="navbar">
    <h5>{{ topics.link }}</h5>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  data() {
    return {
      topics: [
        { link: <a href="https://pucminas.br" target="_blank" rel="noopener">Topic 1</a> },
        { link: <a href="https://take.net" target="_blank" rel="noopener">Topic 2</a>},
        { link: <a href="https://google.com.br" target="_blank" rel="noopener">Topic 3</a>},
        { link: <a href="https://cli.vuejs.org" target="_blank" rel="noopener">Topic 4</a>}
      ]     
    };
  }
}
</script>