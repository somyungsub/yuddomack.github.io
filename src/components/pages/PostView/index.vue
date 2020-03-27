<template>
  <div class="hello">
    <post-header></post-header>
    <post-toc></post-toc>
    <post-content></post-content>
  </div>
</template>

<script>
import PostHeader from '@/components/organism/PostHeader';
import PostToc from '@/components/organism/PostToc';
import PostContent from '@/components/organism/PostContent';

export default {
  name: 'PostView',
  components: {
    PostToc, // PostToc -> post-tOC
    PostHeader,
    PostContent,
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
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
