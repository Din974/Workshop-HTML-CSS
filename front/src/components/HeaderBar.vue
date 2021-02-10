<template>
    <div class="HeaderBar">
        <h1>PostApp</h1>
        <ul>
            <li>Home</li>
            <li><router-link to="/login">Login</router-link></li>
            <li>Sign up</li>
        </ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    .HeaderBar {
        background-color: blue;
        display: flex;
        justify-content: space-around;
    }
    ul {
        display: flex;
        justify-content: space-around;
        width: 300px;
    }
</style>