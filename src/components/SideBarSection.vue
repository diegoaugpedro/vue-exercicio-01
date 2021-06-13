<template>
<div class="section">
    <div class="section-item" v-for="row in sections" :key="row">
      <tr>
        <td>
          <a :href="row.url" target="_blank" rel="noopener">Section</a>
        </td>
      </tr>
      
    </div>
  </div>
</template>

<script>
export default {
  name: "SideBarSection",
  data() {
    return {
      sections: [
        { url: "#1" },
        { url: "#2" },
        { url: "#3" },
        { url: "#4" },
        { url: "#5" },
        { url: "#6" },
        { url: "#7" },
        { url: "#8" },
        { url: "#9" },
        { url: "#10" },
        { url: "#11" },
        { url: "#12" },
        { url: "#13" },
        { url: "#14" },
        { url: "#15" },
      ],
    };
  },
};
</script>