<template>
    <a :href="link" class="btn btn-danger">
        {{ btnTxt }}
    </a>
</template>

<script>
    export default {
        name: 'Button',
        props: {
            btnTxt: {
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

    .btn {
        font-weight: 600;
    }
</style>
