<template>
    <div class="container">
        <wp-header></wp-header>
        <hr>
        <wp-servers></wp-servers>
        <hr>
        <wp-footer></wp-footer>
    </div>
</template>

<script>
    import Header from './Header.vue';
    import Servers from './Servers.vue';
    import Footer from './Footer.vue';

    export default {
        components: {
            'wp-header': Header,
            'wp-servers': Servers,
            'wp-footer': Footer
        }
    }
</script>

<style>

</style>
