<script>
import Description from "./Description.vue";
import Catalog from "./Catalog.vue";
export default {
    name: 'SectionCourses',
    components: {
        Catalog,
        Description
    }
}
</script>

<template>

    <section class="courses">

        <Catalog></Catalog>

        <!-- /.Catalog -->

        <Description></Description>

        <!-- /.Description -->


    </section>
    <!-- /.courses -->

</template>

<style>

</style>