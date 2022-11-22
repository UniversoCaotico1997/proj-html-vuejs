<script>
import InfoCourses from "./InfoCourses.vue";
import SectionFaculties from "./SectionFaculties.vue";
export default {
    name: `AppMain`,
    components: {
        InfoCourses,
        SectionFaculties

    }
}
</script>


<template>
    <main id="site_main">

        <InfoCourses></InfoCourses>

        <!-- /.InfoCourses -->


        <SectionFaculties></SectionFaculties>

        <!-- /.SectionFaculties -->

    </main>
</template>

<style>

</style>