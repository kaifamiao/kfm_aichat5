<template>
  <div class="chat-input">
    <select>
      <option>Option 1</option>
      <option>Option 2</option>
      <option>Option 3</option>
    </select>
    <select>
      <option>Input 1</option>
      <option>Input 2</option>
      <option>Input 3</option>
    </select>
    <textarea placeholder="Type your message here..."></textarea>
    <button @click="sendMessage">Send</button>
  </div>
</template>

<script setup>
const sendMessage = () => {
  console.log('Message sent');
};
</script>

<style scoped>
.chat-input {
  display: flex;
  gap: 10px;
  padding: 10px;
  background-color: #f4f4f4;
  border-top: 1px solid #ccc;
}

.chat-input textarea {
  flex: 1;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.chat-input button {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

.chat-input button:hover {
  background-color: #0056b3;
}
</style>
