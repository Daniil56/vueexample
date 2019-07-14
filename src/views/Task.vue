<template>
    <h1>{{task.title}}</h1>
</template>

<script>
    export default {
        computed: {
           task() {
               return this.$store.getters.taskById()
           }
        }
    }
</script>

<style lang="scss" scoped>

</style>