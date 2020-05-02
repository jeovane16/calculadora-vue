<template>
    <div id="app">
        <h1>Calculator</h1>
        <Calculator/>
    </div>
</template>

<script>
    import Calculator from "./main/Calculator";
    export default {
        name: "App",
        components: {Calculator},
        comments: { Calculator }
    }
</script>

<style scoped>
    @font-face {
        font-family: "Roboto Thin";
        src: url("./fonts/Roboto-Thin.ttf");
    }
    * {
        font-family: "Roboto Thin", monospace;
    }

    body {
        margin: 0;
    }

    #app {
        display: flex;
        flex-direction: column;
        height: 100vh;
        justify-content: center;
        align-items: center;
        text-align: center;

        color: #fff;
        background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
    }
</style>