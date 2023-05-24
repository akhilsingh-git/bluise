<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://github.com/akhilsingh-git">
        <!-- Github SVG here-->
      </a>
      <a href="https://www.linkedin.com/in/akhilisallin/" class="ml-4">
        <svg xmlns="http://www.w3.org/2000/svg" fill="white" width="24px" height="32px" viewBox="0 0 24 24">
            <path d="M0 0h24v24H0z" fill="none"/>
            <path d="M4 4v16h16V16l-2.5-2.5L16 13l2.5-2.5L21 7V4H4zm6 14v-6H7V7h3v5h4V7h3v5l-4 4v2h4v4h-10zm-1-12h-2v2h2V6zM6 2h12a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1z" />
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
