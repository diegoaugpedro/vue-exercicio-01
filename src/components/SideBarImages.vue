<template>
  <div class="section">
    <div class="section-item">
      <tr class="imageItems" v-for="img in imageItems" :key="img">
        <td>
          <img :src="imageItems" />
        </td>
      </tr>
    </div>
  </div>
</template>

<script>
import Batman from "./images/B1.png";
import Superman from "./images/S1.png";
import MulherMaravilha from "./images/M1.jpg";

export default {
  name: "SideBarImages",
  data() {
    return {
      imageItems: [{ src: Batman }, { src: Superman }, { src: MulherMaravilha }],
    };
  },
};
</script>