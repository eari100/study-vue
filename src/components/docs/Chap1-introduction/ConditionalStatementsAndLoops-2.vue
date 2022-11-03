<script>
    export default {
        data() {
            return {
                todos: [
                    { text: 'Learn JavaScript' },
                    { text: 'Learn Vue' },
                    { text: 'Build something awesome' }
                ]
            }
        }
    }
</script>

<template>
    <div id="list-rendering">
        <ol>
            <li v-for="todo in todos">
            {{ todo.text }}
            </li>
        </ol>
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
