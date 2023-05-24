<template>
  <footer class="footer">
    <div class="container">
      <a href="https://github.com/akhilsingh-git">
        <img src="https://image.flaticon.com/icons/png/512/733/733609.png" width="32" height="32">
      </a>
      <a href="https://www.linkedin.com/in/akhilisallin/" class="ml-4">
        <img src="https://image.flaticon.com/icons/png/512/174/174857.png" width="32" height="32">
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
  .container {
    display: flex;
    justify-content: center;
    padding-bottom: 16px;
    a {
      color: white;
    }
    img {
      filter: invert(1); /* This will change the black icon to white */
    }
  }
}
</style>
