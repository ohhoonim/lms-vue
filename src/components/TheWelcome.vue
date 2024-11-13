<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
    </template>
    <template #heading>Documentation</template>
    LMS의
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    을 보시면 쉽게 시작하실 수 있습니다.
  </WelcomeItem>
</template>
