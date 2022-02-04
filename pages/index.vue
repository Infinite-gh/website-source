<template>
<div class="bg-blue-500 w-screen h-screen">
  <Head />
  <NavBar />
  <h1>This is going to be the content</h1>
</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  head() {
    return {
      title: "Welcome to Negative Zero."
    };
  }
})
  
</script>
