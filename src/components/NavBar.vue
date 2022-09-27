<template>
    <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/create">Create</RouterLink>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
nav {
    margin: 10px 0;
    display: flex;
    justify-content: center;
}
nav a{
    text-decoration: none;
    color: #888;
    margin: 0 5px;
    padding: 10px;
    border-radius: 5px;
}
nav a:hover {
    color: #fff;
    background-color: rgb(158, 5, 35);
}
.router-link-active {
    color: #fff;
    background-color: crimson;
}
</style>