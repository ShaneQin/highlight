<script setup>
import HighlightInsert from './components/HighlightInsert.vue'
import HighlightCover from './components/HighlightCover.vue'
</script>

<template>
  <div id="app">
    <div>
      <highlight-insert></highlight-insert>
    </div>
    <div class="highlight-cover">
      <highlight-cover></highlight-cover>
    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  display: flex;
}
.highlight-cover {
  margin-left: 100px;
}
</style>
