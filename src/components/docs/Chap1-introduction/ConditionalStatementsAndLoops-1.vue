<script>
    export default {
        data() {
            return {
                seen: true
            }
        }
    }
</script>

<template>
    <div id="conditional-rendering">
        <span v-if="seen">이제 나를 볼수 있어요</span>
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
