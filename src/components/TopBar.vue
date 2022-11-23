<script>
export default {
    name: `TopBar`,
    data() {
        return {
            menu: [
                {
                    text: `Home`,
                    href: `#`
                },
                {
                    text: `Courses`,
                    href: `#`
                },
                {
                    text: `About Us`,
                    href: ``
                },
                {
                    text: `News`,
                    href: `#`
                },
                {
                    text: `Pages`,
                    href: `#`
                },
                {
                    text: `Contact`,
                    href: `#`
                },
                {
                    text: `Purchase`,
                    href: `#`
                }
            ]
        }
    }
}
</script>


<template>
    <!-- Rimuover container ed utilizzare space around -->
    <section class="top_bar">
        <div class="d-flex justify-content-around my-3">
            <!-- logo -->
            <img src="../assets/img/theme_eduprime_logo.png" alt="">
            <!-- /.logo -->
            <div class="menu d-flex">
                <ul class="d-flex mt-4">
                    <li v-for="item in menu">
                        <a href="#">{{ item.text }}</a>
                    </li>
                </ul>
                <!-- button -->
                <a class=" button text-uppercase align-self-center rounded-pill ms-3" href="#">View Courses</a>
                <!-- /.button -->
            </div>
            <!-- /.menu -->
        </div>
    </section>
    <!-- /.top_bar -->

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
    padding: 0.75rem 1rem;
    background-color: #e9d758;
    text-decoration: none;
    color: white;
}
</style>