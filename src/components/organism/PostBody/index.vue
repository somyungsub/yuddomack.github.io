<template>
  <div class="content">
    <PostToc></PostToc>
    <PostArticle></PostArticle>
  </div>
</template>

<script>
import PostToc from '@/components/molecule/PostToc';
import PostArticle from '@/components/molecule/PostArticle';

export default {
  name: 'PostBody',
  components: {
    PostToc,
    PostArticle,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content {
  padding-left: 100px;
  padding-right: 100px;
  padding-top: 10px;
  /* background: gray; */
}

.content::after {
  content: '';
  display: block;
  clear: both;
}

@media (max-width: 1024px) {
  .content {
    padding: 0;
  }
}
</style>
