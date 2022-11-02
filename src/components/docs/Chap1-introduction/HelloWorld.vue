<script setup>
defineProps({
  message: {
    type: String,
    required: true
  }
})
</script>

<template>
    <div class="demo">
        {{ message }}
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
