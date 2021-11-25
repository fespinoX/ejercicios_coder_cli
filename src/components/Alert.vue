<template>
    <div class="alert mt-3" :class="cssClass" role="alert">
        {{ alertTxt }}
    </div>
</template>

<script>
    export default {
        name: 'Alert',
        props: {
            alertTxt: {
                type: String,
                default: "Danger!"
            },
            cssClass: {
                type: String,
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
