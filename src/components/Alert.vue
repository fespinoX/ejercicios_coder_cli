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
    
    .alert {
        font-weight: 600;
    }
    
    .alert-success {
        background-color: transparent;
        color: #3cb33c;
        border: 1px solid #3cb33c;
    }

</style>
