<script>
    export default {
        data() {
            return {
                title: 'La mia prima app con Vite!'
            }
        },
    }
</script>

<template>

    <h1 class="title">{{ title }}</h1>

</template>

<style scoped>
    .title {
        margin: 50px auto;
        text-align: center;
        font-family: Arial, Helvetica, sans-serif;
    }
    
</style>