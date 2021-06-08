<template>
  <div class="topic">
    <ul>
      <li v-for="topic in topics" :key="topic">
        {{topics.link}}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Topics",
    data() {
    return {
      topics: [
        { link: <a href="https://pucminas.br" target="_blank" rel="noopener">Topic 1</a> },
        { link: <a href="https://take.net" target="_blank" rel="noopener">Topic 2</a>},
        { link: <a href="https://google.com.br" target="_blank" rel="noopener">Topic 3</a>},
        { link: <a href="https://cli.vuejs.org" target="_blank" rel="noopener">Topic 4</a>}
      ]     
    }
  }
}
</script>