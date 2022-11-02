<script setup>
    const message = `You loaded this page on ${new Date().toLocaleString()}`
</script>

<template>
    <div id="bind-attribute">
        <span v-bind:title="message">
            여기에 마우스를 올려두고 잠시 기다리면 제목이 동적으로 바뀝니다!
        </span>
    </div>
</template>

<style scoped>
.demo {
  font-family: sans-serif;
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select: none;
  overflow-x: auto;
}
</style>
