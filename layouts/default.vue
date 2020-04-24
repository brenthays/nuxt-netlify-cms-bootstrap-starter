<template>
  <div>
    <SiteNav />
    <nuxt />
    <SiteFooter />
  </div>
</template>

<script>
import SiteNav from '~/components/SiteNav.vue'
import SiteFooter from '~/components/SiteFooter.vue'

export default {
  components: {
    SiteNav,
    SiteFooter
  }
}
</script>
