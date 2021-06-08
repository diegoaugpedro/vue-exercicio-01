<template>
  <div class="section">
    <ul>
      <li v-for="image in images" :key="image">
        {{ images.image }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "SideBarImages",
  data() {
    return {
      images: [
        { image: "IMAGEM 1" },
        { image: "IMAGEM 2" },
        { image: "IMAGEM 3" },
        { image: "IMAGEM 4" },
      ],
    };
  },
};
</script>