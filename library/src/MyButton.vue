<template>
  <div>
    <button class="button1" v-bind="$attrs">
      <slot />
    </button>
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  inheritAttrs: false,
})
</script>

<style scoped>
.button1 {
  color: darkviolet;
  font-weight: bold;
  border-radius: 5px;
  padding: 5px 25px;
}
</style>
