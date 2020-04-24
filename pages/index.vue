<template>
  <div class="text-center py-5">
    <div class="mb-3">
      <logo />
    </div>
    <h1 class="mb-3">Nuxt.js, Netlify CMS & Bootstrap Starter</h1>
    <div class="deploy-button">
      <a
        href="https://app.netlify.com/start/deploy?repository=https://github.com/brenthays/nuxt-netlify-cms-bootstrap-starter"
      >
        <img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />
      </a>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
}
</script>

<style>
</style>
