<template>
    <div class="section">
      <ul>
        <li v-for="image in images" :key="image">
          {{ image.images }}
        </li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'SideBarImages',
  data() {
      return {
      images:[
        {images: 'IMAGEM 1'},
        {images: 'IMAGEM 2'},
        {images: 'IMAGEM 3'}
      ]}
    }
  }
</script>