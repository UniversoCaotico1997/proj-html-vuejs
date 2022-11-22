<script>
import TopBar from "./TopBar.vue";
import SectionJumbotron from "./SectionJumbotron.vue";
export default {
    name: 'AppHeader',
    components: {
        TopBar,
        SectionJumbotron
    }

}
</script>

<template>
    <header id="site_header">

        <TopBar></TopBar>
        <!-- /.TopBar -->

        <SectionJumbotron></SectionJumbotron>
        <!-- /.SectionJumbotron -->

    </header>
</template>

<style lang="scss" scoped>

</style>