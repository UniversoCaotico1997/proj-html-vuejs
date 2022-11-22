<script>
export default {
    name: 'InfoCourses'
}
</script>

<template>
    <section class="info_courses bg-white">
        <!-- button -->
        <button class="btn btn-dark ms-3">
            <small>
                Purchase EduPrime on Envato
                <br> Market
            </small>
        </button>
        <!-- /.button -->
        <div class="container">
            <div class="icon">
                <img src="../assets/img/Books-icon.png" width="50px" alt="">
            </div>
            <!-- /.icon -->
            <div class="row">
                <div class="col">
                    <h1 class="py-3">Thousand of courses for any type of student</h1>
                    <p class="pb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesentium ducimus
                        sapiente quam ab?
                        Nemo debitis inventore sint obcaecati officiis provident!
                    </p>
                    <a class="button rounded-pill" href="#">Browse through courses</a>
                </div>
                <!-- /.col -->
                <div class="col">
                    <img src="../assets/img/Graduation-Illustration.png" alt="">
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
        </div>
        <!-- /.container -->
    </section>

</template>

<style lang="scss" scoped>
.info_courses {
    background-image: url(../assets);
}

.container {
    width: 70%;
    padding: 7rem 0;

    p {
        font-size: small;
    }

    .button {
        padding: 0.75rem 1rem;
        background-color: #e9d758;
        text-decoration: none;
        color: white;
    }

}
</style>