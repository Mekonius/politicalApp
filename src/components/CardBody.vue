<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'CardBody',
  props: {
    msg1: String,
    msg2: String,
    msg3: String,
  },
})
</script>

<template>
    <div class="flex flex-row">
        <div class="basis-1/4">{{ msg1 }}</div>
        <div class="basis-1/4">{{ msg2 }}</div>
        <div class="basis-1/2">{{ msg3 }}</div>
    </div>
</template>