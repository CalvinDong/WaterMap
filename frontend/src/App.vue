<template>
    <Map/>
</template>

<script>
    import Map from './components/Map.vue';
    import dotenv from 'dotenv';
    dotenv.config();

    export default {
        name: 'App',
        components: {
            Map
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin: 0;
    }
</style>
