<script>
export default {
    name: 'SingleFaculty'
}
</script>

<template>
    <section class="single_faculty bg-white">
        <div class="container">
            <div class="row">
                <div class="col">
                    <img class="" src="../assets/img/Gavel-Illustration-e1556884768193.png" width="60%" alt="">
                </div>
                <!-- /.col -->
                <div class="col">
                    <h2 class="py-3">Law Faculty</h2>
                    <p class="pb-4"> Learning from world-leading academics and practitioners, you'ill not only
                        receive
                        an outstanding grouding in the theory of law, but you will be able to understand
                        how those principles are applied in pratice through a range of student-led
                        activities and competitions.
                    </p>
                    <a class="button rounded-pill" href="#">Read More</a>
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
        </div>
        <!-- /.container -->

    </section>
</template>

<style lang="scss" scoped>
.single_faculty {
    padding-bottom: 6rem;
}

.container {
    width: 70%;

}

img {
    margin-left: 10rem;
}

.button {
    padding: 0.75rem 1rem;
    background-color: #e5768e;
    text-decoration: none;
    color: white;
}

p {
    font-size: small;
}
</style>