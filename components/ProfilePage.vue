<template>
  <v-container>
    <stories-section />
    <feed-section />
  </v-container>
</template>

<script>
import StoriesSection from "./profile/StoriesSection";
import FeedSection from "./profile/FeedSection";
export default {
  components: {
    StoriesSection,
    FeedSection
  }
};
</script>

<style>
</style>