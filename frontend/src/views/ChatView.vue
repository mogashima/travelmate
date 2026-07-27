<template>
  <div class="chat">
    <h1>TravelMate</h1>

    <div class="messages">
      <div class="ai">
        こんにちは！<br />
        旅行について教えてください。
      </div>
    </div>

    <div class="input-area">
      <input
        type="text"
        placeholder="旅行について入力..."
      />

      <button>送信</button>
    </div>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped lang="scss">
.chat {
  max-width: 900px;
  margin: auto;
  padding: 40px;
}

.messages {
  height: 500px;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  margin: 20px 0;
}

.ai {
  background: #f4f4f4;
  padding: 15px;
  border-radius: 8px;
  width: fit-content;
}

.input-area {
  display: flex;
  gap: 10px;

  input {
    flex: 1;
    padding: 12px;
  }

  button {
    width: 120px;
  }
}
</style>