<template>
  <div class="flex flex-col items-center justify-center">
    <h1 class="text-2xl text-blue-700">This is the about page!</h1>
    <h3>
      The slug used in the URL is:
      <span class="text-bold underline">{{ slug }}</span>
    </h3>
  </div>
</template>

<script>
import {useRoute} from 'vue-router';

export default {
  name: 'About',
  setup() {
    const route = useRoute();
    const slug = route.params.slug;
    return {slug};
  },
};
</script>

<style></style>
