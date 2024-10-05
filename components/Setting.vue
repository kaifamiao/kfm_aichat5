<template>
  <div class="setting">
    <button @click="openSettings">Settings</button>
  </div>
</template>

<script setup>
const openSettings = () => {
  console.log('Open settings');
};
</script>

<style scoped>
.setting {
  margin-top: 10px;
}

.setting button {
  width: 100%;
  padding: 10px;
  background-color: #6c757d;
  color: white;
  border: none;
  cursor: pointer;

}

.setting button:hover {
  background-color: #5a6268;
}
</style>
