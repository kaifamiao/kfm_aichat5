<template>
  <div class="chat-list">
    <div v-for="chat in chats" :key="chat.id" class="chat-item">
      {{ chat.title }}
    </div>
  </div>
</template>

<script setup>
const chats = Array.from({ length: 100 }, (_, index) => ({
  id: index + 1,
  title: `Chat ${index + 1}`
}));
</script>

<style scoped>
.chat-list {
  padding: 10px;
}

.chat-item {
  padding: 5px;
  border-bottom: 1px solid #ccc;
}
</style>
