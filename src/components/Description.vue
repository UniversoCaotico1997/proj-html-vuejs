<script>
export default {
    name: 'Description'
}
</script>

<template>
    <div class="description bg-white">
        <div class="container py-5">
            <div class="row">
                <div class="col">
                    <img src="../assets/img/Exam-icon.png" width="80px" alt="">
                    <h2 class="py-3">The most efficent examination method</h2>
                    <p class="pb-4">EduPrime has gathered teachers from around the globe to
                        <br> brainstorm in order to facilitate the evulation of our students.
                        <br> Every techer from our university has an influence on how
                        <br> students are evaluated at his/her
                        subject.
                    </p>
                    <a class="button rounded-pill" href="#">Discover the Method</a>
                </div>
                <!-- /.col -->
                <div class="col">
                    <img src="../assets/img/Exam-Illustration.png" alt="">
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
            <div class="row mt-4 g-5">
                <div class="col">
                    <img src="../assets/img/Girl-Illustration.png" alt="">
                </div>
                <!-- /.col -->
                <div class="col">
                    <img src="../assets/img/Exam-icon-1.png" width="80px" alt="">
                    <h2 class="py-3">Variables fee for international students</h2>
                    <p class="pb-4">EduPrime has gathered teachers from around the globe to
                        <br> brainstorm in order to facilitate the evulation of our students.
                        <br> Every techer from our university has an influence on how
                        <br> students are evaluated at his/her
                        subject.
                    </p>
                    <a class="button rounded-pill" href="#">List of Fees</a>
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
        </div>
        <!-- /.container -->


    </div>
    <!-- /.description -->
</template>

<style lang="scss" scoped>
@use'../assets/partial/container';

.button {
    padding: 0.75rem 1rem;
    background-color: #DB2A2C;
    text-decoration: none;
    color: white;
}
</style>