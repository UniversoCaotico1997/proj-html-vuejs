<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
    name: 'App',
    components: {
        AppHeader,
        AppMain,
        AppFooter

    }
}

</script>

<template>

    <AppHeader></AppHeader>
    <!-- /.site_header -->


    <AppMain></AppMain>
    <!-- /.site_main -->


    <AppFooter></AppFooter>
    <!-- /.site_footer -->

</template>

<style>

</style>
