<template>
  <nuxt-link class="underline font-medium" :href="firstLesson.path">
    Go to first Lesson
  </nuxt-link>
</template>
<script setup lang="ts">
const firstLesson = useFirstLesson();
</script>
