<template>
  <button class="new-chat" @click="createNewChat">New Chat</button>
</template>

<script setup>
const createNewChat = () => {
  console.log('Create new chat');
};
</script>

<style scoped>
.new-chat {
  width: 100%;
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

.new-chat:hover {
  background-color: #0056b3;
}
</style>
