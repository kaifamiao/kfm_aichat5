<template>
  <div class="main-header">
    <button @click="toggleSidebar">≡</button>
    <select>
      <option>Model</option>
    </select>
    <select>
      <option>Prompt</option>
    </select>
    <select>
      <option>Knowledge Base</option>
    </select>
  </div>
</template>

<script setup>
const toggleSidebar = () => {
  const sidebar = document.querySelector('.sidebar');
  sidebar.style.display = sidebar.style.display === 'none' ? 'block' : 'none';
};
</script>

<style scoped>
.main-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  background-color: #f4f4f4;
  border-bottom: 1px solid #ccc;
}

.main-header button {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 5px 10px;
  cursor: pointer;
}

.main-header button:hover {
  background-color: #0056b3;
}
</style>
