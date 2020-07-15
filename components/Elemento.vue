<template>
  <div class="feed-post">
    <div class="feed-post__titulo">{{titulo}}</div>
    <div class="feed-post__texto">{{projeto}}</div>
  </div>
</template>

<script lang="ts">
import Vue, { PropOptions } from "vue";
export default Vue.extend({
    props: {
        titulo:{ },
        projeto: { }
    }
});
</script>

<style scoped>
.feed-post {
  margin: 20px 0;
  cursor: pointer;
}

.feed-post:hover .feed-post__titulo {
  color: royalblue;
}

.feed-post__titulo {
  font-size: larger;
  font-weight: bold;
  margin-bottom: 0.5rem;
}

.feed-post__texto {
  font-style: italic;
}
</style>