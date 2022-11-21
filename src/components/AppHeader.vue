<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header id="site_header">
        <div class="menu">
            <div class="container d-flex justify-content-between mt-5">

                <img src="../assets/img/theme_eduprime_logo.png" alt="">

                <!-- /.left -->
                <div class="right d-flex">
                    <ul class="d-flex mt-3">
                        <li>
                            <a href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">Courses</a>
                        </li>
                        <li>
                            <a href="#">About Us</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                        <li>
                            <a href="#">Pages</a>
                        </li>
                        <li>
                            <a href="#">Contact</a>
                        </li>
                        <li>
                            <a href="#">Purchase</a>
                        </li>
                    </ul>
                    <div class="align-self-center ">
                        <a class=" button text-uppercase align-self-center rounded-pill" href="#">View Courses</a>
                    </div>
                </div>



                <!-- /.right -->
            </div>
            <!-- /.menu -->
        </div>
        <!-- /.contanier -->
    </header>
</template>

<style lang="scss" scoped>
img {
    width: 20%;
}

ul {
    list-style: none;

    li {
        margin: 0 0.50rem;

        a {
            text-decoration: none;
            color: white;

            &:hover {
                color: #e9d758;
            }
        }
    }

}

.button {
    padding: 1rem;
    background-color: #e9d758;
    text-decoration: none;
    color: white;
}
</style>