<script>
export default {
    name: 'Description'
}
</script>
<template>
    <div class="description bg-white pb-5">
        <div class="container">
            <!-- title section -->
            <h1 class=" py-5">Latest Courses</h1>
            <!-- /.title section -->
            <div class="shop d-flex justify-content-center gap-4">
                <div class="decisions bg-white text-center px-2">
                    <img src="../assets/img/Decisions-icon.png" alt="">
                    <h5 class="py-2">Make Better Decisions</h5>
                    <p>Teacher: James Collins</p>
                    <p>Price:$21.00</p>
                    <a class="button rounded-pill" href="#">View Course</a>
                </div>
                <!-- /.decisions -->
                <div class="speaker bg-white text-center px-2">
                    <img src="../assets/img/Speaker-icon.png" alt="">
                    <h5 class="py-2">How to be a speaker</h5>
                    <p>Teacher: James Collins</p>
                    <p>Price: Free</p>
                    <a class="button rounded-pill" href="#">View Course</a>
                </div>
                <!-- /.speaker -->
                <div class="network bg-white text-center px-2">
                    <img src="../assets/img/Network-icon.png" alt="">
                    <h5 class="py-2">Coaching Session</h5>
                    <p>Teacher: James Collins</p>
                    <p>Price: Free</p>
                    <a class="button rounded-pill" href="#">View Course</a>
                </div>
                <!-- /.network -->
                <div class="brand bg-white text-center px-2">
                    <img src="../assets/img/Brand-icon.png" alt="">
                    <h5 class="py-2">Coaching Session</h5>
                    <p>Teacher: James Collins</p>
                    <p>Price: Free</p>
                    <a class="button rounded-pill" href="#">View Course</a>
                </div>
                <!-- /.brand -->
            </div>
            <!-- /.shop -->




        </div>

    </div>

</template>

<style lang="scss" scoped>
@use'../../src/assets/partial/container';

img {
    width: 70px;
    padding-bottom: 0.5rem;
}

.button {
    padding: 0.75rem 1rem;
    text-decoration: none;
    color: white;
    background-color: #DB2A2C;
    display: inline-block;
}
</style>