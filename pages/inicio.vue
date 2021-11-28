<script>
import menuLeft from "../components/menuleft.vue";
import Post from "../components/post.vue";
export default {
  components: { menuLeft, Post },
};
</script>
<template>
  <div>
    <menu />
  
    <menuleft />
    <post />
    <post1 />
    <post2 />
  </div>
</template>

<style>
body{
  background-color: black;
}
</style>