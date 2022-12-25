<template>
    <button @click = "onClick()">{{ id }}</button>
</template>
<script>
export default {
    name: "Button",
    methods: {
        onClick(){
            console.log(this.id)
        }
    },
    props:["id", "number"]
}
</script>