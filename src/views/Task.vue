<template>
    <h1>{{task.title}}</h1>
</template>

<script>
    export default {
        computed: {
            task() {
                return this.$store.getters.taskById(+this.$route.params.id)
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>