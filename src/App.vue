<template>
<div>
    <Leaderboard />
</div>
</template>

<script>
import Leaderboard from "./components/Leaderboard";
export default {
    name: "App",
    components: {
        Leaderboard,
    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
