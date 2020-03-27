<template>
  <div class="post-view">
    <post-header></post-header>
    <post-body></post-body>
  </div>
</template>

<script>
import PostHeader from '@/components/organism/PostHeader';
import PostBody from '@/components/organism/PostBody';

export default {
  name: 'PostView',
  components: {
    PostHeader,
    PostBody,
  },
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* @media (min-width: 1024px) {
  header {
    width: 1024px;
  }
} */
</style>
