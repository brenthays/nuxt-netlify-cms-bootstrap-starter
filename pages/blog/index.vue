<template>
  <div class="container py-5">
    <h1 class="mb-3">Blog Posts</h1>
    <div v-for="(blogPost, index) in blogPosts" :key="index">
      <nuxt-link :to="`blog/${blogPost.slug}`">{{blogPost.title}}</nuxt-link>
      <p>{{blogPost.description}}</p>
    </div>
  </div>
</template>
<script>
export default {
  computed: {
    blogPosts() {
      return this.$store.state.blogPosts
    }
  }
}
</script>
