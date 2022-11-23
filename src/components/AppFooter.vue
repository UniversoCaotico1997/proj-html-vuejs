<script>
import Networking from "../assets/js/Networking";
import link from "../assets/js/link";
export default {
    name: 'AppFooter',
    data() {
        return {
            link,
            Networking
        }
    }
}
</script>

<template>
    <footer id="site_footer">
        <div class="container">
            <div class="row pt-5 text-white">
                <div class="col-3">
                    <img src="../assets/img/theme_eduprime_logo.png" alt="">
                    <p class="py-4 text-white">EduPrime is the most versatile WordPress theme for
                        educational purpose, showcasing universities,
                        course, secondary school etc.
                    </p>
                    <div class="social d-flex gap-3 ">
                        <div class="circle facebook rounded-circle">
                            <i class="fa fa-facebook" aria-hidden="true"></i>
                        </div>
                        <!-- /.facebook -->
                        <div class=" circle twitter rounded-circle">

                        </div>
                        <!-- /.twitter -->
                        <div class=" circle intagram rounded-circle">

                        </div>
                        <!-- /.intagram -->
                    </div>
                    <!-- /.social -->
                </div>
                <!-- /.col -->
                <div class="col-3">
                    <h5 class="mb-4 ms-4">Get EduPrime</h5>
                    <ul>
                        <li v-for="item in link">
                            {{ item.text }}
                        </li>
                    </ul>
                </div>
                <!-- /.col -->
                <div class="col-3">
                    <h5 class="mb-4 ms-4">Networking</h5>
                    <ul>
                        <li v-for="item in Networking">
                            {{ item.text }}
                        </li>
                    </ul>
                </div>
                <!-- /.col -->
                <div class="col-3">
                    <div class="square position-relative">
                        <input class="custom rounded-pill" type="text" placeholder="Search...">
                        <div class=" search rounded-circle "></div>
                    </div>
                    <!-- /.square -->
                    <h5 class="mt-4 text-end">Search categories</h5>

                    <div class="various_faculties d-flex flex-wrap justify-content-end text-uppercase">
                        <div class="faculties rounded-pill">
                            <small>economy</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>designe</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>coaching</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>business</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>medicine</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>fitness</small>
                        </div>
                        <div class="faculties rounded-pill">
                            <small>law</small>
                        </div>
                    </div>
                    <!-- /.various_faculties -->
                </div>
                <!-- /.col -->
            </div>
            <!-- /.row -->
        </div>
        <!--/. container -->
    </footer>
</template>

<style lang="scss" scoped>
@use'../assets/partial/container';

ul {
    list-style-type: none;
}

.custom {
    padding: 1rem;
}

.search {
    position: absolute;
    top: 0;
    right: -17px;
    width: 60px;
    height: 60px;
    background-color: #E9D758;
}

.faculties {
    padding: 2px 6px;
    border: 1px solid white;
    margin: 0.50rem;
}

.circle {
    width: 60px;
    height: 60px;
    border: 1px solid #E9D758;
}
</style>