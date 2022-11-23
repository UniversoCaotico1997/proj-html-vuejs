<script>
import SingleFaculty from "./SingleFaculty.vue";
export default {
    name: 'Faculties',
    components: {
        SingleFaculty
    }
}
</script>

<template>
    <section class="faculties bg-white pb-5">
        <!-- Title section -->
        <h2 class="text-center pb-3">Faculties avaiable at EduPrime</h2>
        <p class="text-center  pb-3">A single university with a load of courses, tailored
            <br> to satisfy any student's need
        </p>
        <!-- /.Title section -->
        <div class="box d-flex justify-content-center align-items-center">
            <div class="square text-center">
                <img src="../assets/img/Gavel-v2.png" alt="">
                <p>Low Faculty</p>
            </div>
            <!-- /.square -->
            <div class="square text-center">
                <img src="../assets/img/Coins-tabs-v2.png" alt="">
                <p>Economy</p>
            </div>
            <!-- /.square -->
            <div class="square text-center">
                <img src="../assets/img/Medicine-tabs-v2.png" alt="">
                <p>Medicine</p>
            </div>
            <!-- /.square -->
            <div class="square text-center">
                <img src="../assets/img/Computer-tabs-v2.png" alt="">
                <p>Computer Science</p>
            </div>
            <!-- /.square -->
            <div class="square text-center">
                <img src="../assets/img/Palette-tabs-v2.png" alt="">
                <p>Graphic Design</p>
            </div>
            <!-- /.square -->
        </div>
        <!-- /.box -->
    </section>
    <!-- /.faculty -->

    <SingleFaculty></SingleFaculty>

    <!-- /.SingleFaculty -->

</template>

<style lang="scss" scoped>
.square {
    width: 200px;
    height: 150px;
    border: 1px solid #ececee;

    img {
        width: 40%;
        margin: 1rem;
    }

    p {
        color: #e5768e;

    }
}
</style>