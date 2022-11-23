<script>
import Description from "./Description.vue";
import Catalog from "./Catalog.vue";
import Subscribe from "./Subscribe.vue";
export default {
    name: 'SectionCourses',
    components: {
        Catalog,
        Description,
        Subscribe
    }
}
</script>

<template>

    <section class="courses">

        <Catalog></Catalog>

        <!-- /.Catalog -->

        <Description></Description>

        <!-- /.Description -->

        <Subscribe></Subscribe>

        <!-- /.Subscribe -->

    </section>
    <!-- /.courses -->

</template>

<style>

</style>