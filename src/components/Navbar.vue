<template>
    <nav class="blue darken-3">
        <div class="nav-wrapper ">
            <router-link to="/" class="brand-logo">Tasks</router-link>
            <ul class="right hide-on-med-and-down">
                <router-link
                    tag="li"
                    to="/"
                    exact
                    acive-class="acive"
                    >
                    <a href="#">Create</a>
                </router-link>
                <router-link
                        tag="li"
                        to="/list"
                        acive-class="acive"
                >
                    <a href="#">List</a>
                </router-link>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>
nav {
    padding: 0 2rem;
}
</style>