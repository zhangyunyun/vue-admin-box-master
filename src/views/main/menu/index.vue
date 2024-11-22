<template>
  <div class="box">
    <router-view></router-view>  
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  setup() {

  }
})
</script>

<style lang="scss" scoped>
  .box {
    padding: 15px;
  }
</style>