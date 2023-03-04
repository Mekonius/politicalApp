<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'CardHeader',
  props: {
    msg: String,
  },
})
</script>

<template>
    <div class="cardHeader">
        <h1>
        {{ msg }}
        </h1>
    </div>
</template>