<template>
  <div class="container">
    <first-components />
    <!-- 鑫鑫 -->
  </div>
</template>

<script>
import FirstComponents from '~/components/FirstComponents/FirstComponents.vue'
export default {
  components: {
    FirstComponents
  }
}
</script>

<style lang="less" scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
