<template>
    <div class="component">
        <h3>You may view the User Details here</h3>
        <p>User name: {{ nombre }}</p>
    </div>
</template>

<script>
    export default {
        props: ['nombre']
    }
</script>

<style scoped>
    div {
        background-color: lightcoral;
    }
</style>
