<template>
    <h1>{{titleText}}</h1>
</template>

<script>
    export default {
        name: 'AppTitle',
        data(){
            return {
                titleText: 'La mia prima app con Vite!'
            }
        },
    }
</script>

<style lang="css">
    h1 {
        background-color: #41B884;
        color: white;
        padding: 1rem;
        text-align: center;
        font-size: 3rem;
    }
</style>