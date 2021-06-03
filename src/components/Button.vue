<template>
    <button @click="onClick()" class = "btn" :style="{background: color}">
        {{title}}
    </button>
</template>

<script>
    export default {
        name: "Button",
        props: {
            title: String,
            color: String
        },
        methods: {
            onClick() {
                console.log("here")
            }
        }
        
    }
</script>
