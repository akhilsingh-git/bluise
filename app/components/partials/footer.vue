<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://github.com/akhilsingh-git">
        <svg
          baseProfile="tiny"
          height="32px"
          fill="white"
          version="1.1"
          viewBox="0 0 24 24"
          width="24px"
          xml:space="preserve"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
        >
          <!-- GitHub SVG Path -->
        </svg>
      </a>
      <a href="https://www.linkedin.com/in/akhilisallin/">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="24px" height="32px">
            <path d="M0 0h24v24H0z" fill="none"/>
            <path d="M4 4v16h16V4H4zm1.41 2h3.17v2.138c.208-.253.562-.543 1.199-.543.946 0 1.65.617 1.65 1.922V14h3.238V8.984c0-2.17-1.155-3.356-3.014-3.356-1.392 0-2.085.785-2.437 1.204V6H5.41V6z"/>
        </svg>
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
}
</style>
