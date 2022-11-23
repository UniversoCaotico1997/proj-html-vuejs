<script>
import SectionIntroduction from "./Sectionintroduction.vue";
import SectionUniversity from "./SectionUniversity.vue";

export default {
    name: `AppMain`,
    components: {
        SectionIntroduction,
        SectionUniversity

    }
}
</script>


<template>
    <main id="site_main">

        <SectionIntroduction></SectionIntroduction>

        <!-- /.SectionIntroduction -->

        <SectionUniversity></SectionUniversity>

        <!-- /.SectionUniversity -->

    </main>

</template>

<style>

</style>