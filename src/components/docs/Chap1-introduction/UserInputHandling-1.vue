<script>
    export default {
        data() {
            return {
                message: 'Hello Vue.js!'
            }
        },
        methods: {
            reverseMessage() {
            this.message = this.message
                .split('')
                .reverse()
                .join('')
            }
        }
    }
</script>

<template>
    <div id="event-handling" class="demo">
        <p>{{ message }}</p>
        <button @click="reverseMessage">Reverse Message</button>
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
