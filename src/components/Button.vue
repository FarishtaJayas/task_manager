<template>
    <button 
    :style="{ background:color }" 
    :click="onClick()"
    class="btn">{{text}}</button>
</template>

<script>
    export default {
        name: 'Button',
        props: {
            text: String,
            color: String
        },

        methods: {
            onClick() {
                console.log('Click')
            }
        }
    }

</script>

<style>

</style>

