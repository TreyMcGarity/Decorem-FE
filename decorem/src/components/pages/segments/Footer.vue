<template>
  <footer>
    <p>Footer</p>
  </footer>
</template>

<script>
export default {
  name: 'Header',
  props: {
      title: String,
  },
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-bottom: 20px;
}
</style>