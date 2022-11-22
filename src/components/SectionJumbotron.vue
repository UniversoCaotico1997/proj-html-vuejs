<script>
export default {
    name: `SectionJumbotron`
}
</script>

<template>
    <section class="jumbotron py-5">
        <div class="container">
            <div class="box text-center py-5">
                <h1 class="text-white mb-5 ">Key to your success</h1>
                <p class="text-white mb-5 ">EduPrime is the most versatile WordPress theme for educational purposes,
                    <br> showcasing universities, courses, secondary schools etc.
                </p>
                <a class=" button left rounded-pill me-5" href="">Seach courses</a>
                <a class=" button right rounded-pill" href="">Apply for university</a>
            </div>
            <!-- /.box -->
        </div>


    </section>
</template>


<style lang="scss" scoped>
.jumbotron {
    background-image: url(../assets/img/theme_slider2_bg-1.jpg);
    background-size: 100%;
    background-position: center right;

}

.button {
    padding: 1rem;
    text-decoration: none;
}

.right {
    background-color: white;
    color: #e56768;
}

.left {
    background-color: #e9d758;
    color: white;
}
</style>