<template>
  <div class="footer py-5 bg-dark text-light text-center">
    <div class="container">
      Copyright © 2020
    </div>
  </div>
</template>
<script>
export default {
  name: 'SiteFooter',

}
</script>
<style lang="scss" scoped>
  @import '@/assets/scss/theme.scss';

  // Box shadow extends footer to bottom of page
  .footer {
    box-shadow: 0 50vh 0 50vh $dark;
  }
</style>
