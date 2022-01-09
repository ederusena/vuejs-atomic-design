<template>
  <div class="component">
    <logo />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'

export default defineComponent({
  components: {
    Logo
  }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
