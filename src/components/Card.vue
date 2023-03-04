<script>
import { defineComponent } from 'vue'
import CardBody from './CardBody.vue';
import CardHeader from './CardHeader.vue';

export default defineComponent({
    name: "Card",
    props: {
        msg: String,
    },
    components: { CardHeader, CardBody }
})
</script>


<template>
    <CardHeader msg="Card Header"/>
    <CardBody msg1="Card Body 1" msg2="Card Body 2" msg3="Card Body 3"/>
    <CardFooter msg="Card Footer"/>
</template>