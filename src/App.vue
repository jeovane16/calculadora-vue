<template>
    <div id="App">
        <h1>Hello World</h1>
    </div>
</template>

<script>
    export default {
        name: "App"
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

#App {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-content: center;
    text-align: center;

    color: #fff;
    background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>