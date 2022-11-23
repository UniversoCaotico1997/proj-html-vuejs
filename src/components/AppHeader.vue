<script>
import TopBar from "./TopBar.vue";
import Jumbotron from "./Jumbotron.vue";
export default {
    name: 'AppHeader',
    components: {
        TopBar,
        Jumbotron
    }

}
</script>

<template>
    <header id="site_header">

        <TopBar></TopBar>
        <!-- /.TopBar -->

        <Jumbotron></Jumbotron>
        <!-- /.Jumbotron -->

    </header>
</template>

<style lang="scss" scoped>

</style>