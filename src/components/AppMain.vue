<script>
import SectionIntroduction from "./Sectionintroduction.vue";
import SectionUniversity from "./SectionUniversity.vue";
import SectionCourses from "./SectionCourses.vue";

export default {
    name: `AppMain`,
    components: {
        SectionIntroduction,
        SectionUniversity,
        SectionCourses

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

    </main>

</template>

<style>

</style>