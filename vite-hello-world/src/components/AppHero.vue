<script>
    import AppTitle from './AppTitle.vue';

    export default {
        data () {
            return {

            }
        },
        components: { AppTitle },
    }
</script>

<template>
    <div class="container">
        <div class="filter">
            <AppTitle id="title"/>
        </div>
    </div>
</template>

<style scoped>
    #title {
        margin-top: 0;
    }

    .filter {
        margin: 0 auto;
        /* border: 1px solid white; */
        width: 500px;
        height: 100px;
        line-height: 90px;
        backdrop-filter: blur(10px);
    }

    .container {
        margin: 50px auto;
        /* border: 1px solid black; */
        width: 80%;
        height: 400px;
        background-image: url(https://images.unsplash.com/photo-1448375240586-882707db888b?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
        background-position: center;
        text-align: center;
        color: white;

        display: flex;
        align-items: center;
    }
</style>