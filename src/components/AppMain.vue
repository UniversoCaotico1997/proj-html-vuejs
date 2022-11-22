<script>
import SectionInfo from "./SectionInfo.vue";
import SectionFaculties from "./SectionFaculties.vue";
import SectionUniversity from "./SectionUniversity.vue";

export default {
    name: `AppMain`,
    components: {
        SectionInfo,
        SectionFaculties,
        SectionUniversity

    }
}
</script>


<template>
    <main id="site_main">

        <SectionInfo></SectionInfo>

        <!-- /.SectionInfo -->

        <SectionFaculties></SectionFaculties>

        <!-- /.SectionFaculties -->

        <SectionUniversity></SectionUniversity>

        <!-- /.SectionUniversity -->



    </main>
</template>

<style>

</style>