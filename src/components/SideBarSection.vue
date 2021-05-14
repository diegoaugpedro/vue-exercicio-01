<template>
    <div class="section">
      <ul>
        <li v-for="section in sections" :key="section">
          {{ section.link }}
        </li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'SideBarSection',
  data() {
      return {
      sections:[
        {link: 'Section 1', url: '#1'},
        {link: 'Section 2', url: '#2'},
        {link: 'Section 3', url: '#3'},
        {link: 'Section 4', url: '#4'},
        {link: 'Section 5', url: '#5'},
        {link: 'Section 6', url: '#6'},
        {link: 'Section 7', url: '#7'},
        {link: 'Section 8', url: '#8'},
        {link: 'Section 9', url: '#9'},
        {link: 'Section 10', url: '#10'},
        {link: 'Section 11', url: '#11'},
        {link: 'Section 12', url: '#12'},
        {link: 'Section 13', url: '#13'},
        {link: 'Section 14', url: '#14'},
        {link: 'Section 15', url: '#15'}
      ]}
    }
  }
</script>