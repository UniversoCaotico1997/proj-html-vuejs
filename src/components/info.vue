<script>
export default {
    name: 'Info'
}
</script>

<template>
    <div class="info bg-white">
        <div class="box text-white text-center rounded bg-dark ms-3">
            <p>
                Purchase EduPrime on Envato Market
            </p>
        </div>
        <!-- /.box -->
        <div class="container py-5">
            <div class="row">
                <div class="col">
                    <img src="../assets/img/Books-icon.png" width="80px" alt="">
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
    </div>
</template>

<style lang="scss" scoped>
@use'../assets/partial/container';

.box {
    width: 180px;

    p {
        font-size: x-small;
    }

}

p {
    font-size: small;
}

.button {
    padding: 0.75rem 1rem;
    background-color: #e9d758;
    text-decoration: none;
    color: white;
}
</style>