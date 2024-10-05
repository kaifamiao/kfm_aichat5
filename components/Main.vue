<template>
  <main class="main">
    <MainHeader />
    <MainContent />
    <ChatInput />
  </main>
</template>

<script setup>
import MainHeader from './MainHeader.vue';
import MainContent from './MainContent.vue';
import ChatInput from './ChatInput.vue';
</script>

<style scoped>
.main {
  flex: 1;
  display: flex;
  flex-direction: column;
  padding: 10px;
}
</style>
