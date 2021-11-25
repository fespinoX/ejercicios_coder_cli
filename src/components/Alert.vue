<template>
    <div class="alert alert-success mt-3" role="alert">
        {{ alerttxt }}
    </div>
</template>

<script>
    export default {
        name: 'Alert',
        props: {
            alerttxt: {
                type: String,
                default: "Danger!"
            },
        }
    }
</script>

<style scoped>


</style>
