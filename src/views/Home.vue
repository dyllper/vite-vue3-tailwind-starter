<template>
  <div class="flex flex-col items-center justify-center p-4">
    <h1 class="text-2xl text-red-700">This is the home page!</h1>
    <router-link class="mt-4 text-purple-700 underline text-xl" to="/about/test"
      >About Test</router-link
    >
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

<style></style>
