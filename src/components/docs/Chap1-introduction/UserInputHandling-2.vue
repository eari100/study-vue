<script>
    export default {
        data() {
            return {
                message: 'Hello Vue!'
            }
        }
    }
</script>

<template>
    <div id="two-way-binding">
        <p>{{ message }}</p>
        <input v-model="message" />
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
