<template>
  <div class="main-content">
    <Chat v-if="isNewChat" />
    <HistoryChat v-else />
  </div>
</template>

<script setup>
import Chat from './Chat.vue';
import HistoryChat from './HistoryChat.vue';

const isNewChat = true; // 根据实际情况切换
</script>

<style scoped>
.main-content {
  flex: 1;
  padding: 10px;
  overflow-y: auto;
}
</style>
