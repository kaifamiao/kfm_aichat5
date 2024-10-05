<template>
  <div class="history-container">
    <ChatList />
  </div>
</template>

<script setup>
import ChatList from './ChatList.vue';
</script>

<style scoped>
.history-container {
  height: 500px;
  overflow-y: auto; /* 添加垂直滚动条 */
  margin-bottom: 10px;
}
</style>
