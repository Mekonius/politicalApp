<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'CardFooter',
  props: {
    msg: String,
  },
})
</script>

<template>
    <div class="cardFooter">
        <h1>
        {{ msg }}
        </h1>
    </div>
</template>