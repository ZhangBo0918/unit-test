<template>
  <div>
    <span>Count:{{ count }}</span>
    <button @click="count++">按钮</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style scoped>
</style>