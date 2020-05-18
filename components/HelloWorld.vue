<template>
  <div>
    <h1>{{ helloWorld }}</h1>
  </div>
</template>
<script lang="ts">
import { ref } from '@vue/composition-api'
export default {
  name: '',
  setup() {
    const helloWorld = ref('Hello, world!')
    return {
      helloWorld
    }
  }
}
</script>
<style lang="scss" scoped></style>
