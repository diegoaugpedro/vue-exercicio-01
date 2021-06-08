<template>
  <div class="article">
    <ul>
      <li v-for="text in articles" :key="text">
        {{text.text}}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Articles",
    data() {
    return {
      articles: [
        { text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Et explicabo molestiae enim vel praesentium repudiandae, iste voluptatum, accusantium exercitationem modi ab pariatur voluptates est, eius quisquam veniam atque quam itaque! Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore animi illum ut, quo minima optio nisi, illo blanditiis quia perferendis ipsam. Voluptatibus dolores veritatis rem, id totam illo at facilis."},
        { text: "----------------------------------------------------------------------------------------------"},
        { text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Et explicabo molestiae enim vel praesentium repudiandae, iste voluptatum, accusantium exercitationem modi ab pariatur voluptates est, eius quisquam veniam atque quam itaque! Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias minima voluptas repellat. Magnam cumque aliquid consectetur! Qui, tempore vero amet, sunt suscipit pariatur reprehenderit perspiciatis beatae voluptate neque officia quibusdam?"},
        { text: "----------------------------------------------------------------------------------------------"},
        { text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Et explicabo molestiae enim vel praesentium repudiandae, iste voluptatum, accusantium exercitationem modi ab pariatur voluptates est, eius quisquam veniam atque quam itaque! Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iste, beatae! Doloremque consequatur debitis recusandae, quo necessitatibus facere nihil quod mollitia. Incidunt repudiandae ad ducimus accusantium consequatur placeat earum quaerat? Sint?"}
      ],
    };
  },
};
</script>

<style scoped>
li {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  list-style-type: none;
}
</style>