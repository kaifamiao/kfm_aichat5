<template>
  <aside class="sidebar">
    <NewChat />
    <HistoryContainer />
    <Setting />
  </aside>
</template>

<script setup>
import NewChat from './NewChat.vue';
import HistoryContainer from './HistoryContainer.vue';
import Setting from './Setting.vue';
</script>

<style scoped>
.sidebar {
  width: 250px;
  background-color: #f4f4f4;
  padding: 10px;
  overflow: hidden;

  display: flex;
  flex-direction: column;
  justify-content: space-between;

}

@media (max-width: 768px) {
  .sidebar {
    display: none;
  }
}
</style>
