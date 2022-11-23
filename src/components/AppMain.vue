<script>
import SectionIntroduction from "./SectionIntroduction.vue";
import SectionUniversity from "./SectionUniversity.vue";
import SectionCourses from "./SectionCourses.vue";
import SectionPartners from "./SectionPartners.vue";
export default {
    name: `AppMain`,
    components: {
        SectionIntroduction,
        SectionUniversity,
        SectionCourses,
        SectionPartners

    }
}
</script>


<template>
    <main id="site_main">

        <SectionIntroduction></SectionIntroduction>

        <!-- /.SectionIntroduction -->

        <SectionUniversity></SectionUniversity>

        <!-- /.SectionUniversity -->

        <SectionCourses></SectionCourses>

        <!-- /.SectionCourses -->

        <SectionPartners></SectionPartners>

        <!-- /.SectionPartners -->

    </main>

</template>

<style>

</style>