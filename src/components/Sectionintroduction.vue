<script>
import Faculties from "./Faculties.vue";
import Info from "./info.vue";
export default {
    name: 'SectionIntroduction',
    components: {
        Info,
        Faculties
    }
}
</script>

<template>
    <!-- Rinominare il componente Info in Introduzione e creare un componente info -->
    <section class="introduction">

        <Info></Info>
        <!-- /.info -->

        <Faculties></Faculties>

        <!-- /.SectionFaculties -->

    </section>
    <!-- /.introduction -->

</template>

<style>

</style>