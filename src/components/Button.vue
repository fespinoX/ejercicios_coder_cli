<template>
    <a :href="link" class="btn btn-danger">
        {{ btntxt }}
    </a>
</template>

<script>
    export default {
        name: 'Button',
        props: {
            btntxt: {
                type: String,
                default: "Click acá"
            },
            link: {
                type: String,
                default: "#"
            }
        }
    }
</script>

<style scoped>


</style>
