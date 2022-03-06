<template>
  <b-container fluid>
    <Header />
    <b-row class="py-3">
      <PostContent />
      <PostContent />
    </b-row>
  </b-container>
</template>

<script>
import Header from "@/components/Header";
import PostContent from "@/components/PostContent";
export default {
  layout: "default",
  components: {
    Header,
    PostContent,
  },
};
</script>

<style>
html {
  align-content: center;
}
</style>