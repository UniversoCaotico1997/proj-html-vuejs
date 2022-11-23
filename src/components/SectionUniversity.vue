<script>
import Year from "./Year.vue";
import Events from "./Events.vue";
export default {
    name: 'SectionUniversity',
    components: {
        Events,
        Year
    }
}
</script>

<template>

    <section class="university">


        <Year></Year>
        <!-- /.year -->

        <Events></Events>

        <!--/. SectionEvents -->


    </section>
    <!--/. SectionUniversity -->


</template>

<style>

</style>
