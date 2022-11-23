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
            <div class="row mt-5 text-white">
                <div class="col-3">
                    <img src="../assets/img/theme_eduprime_logo.png" alt="">
                    <p class="py-4 text-white">EduPrime is the most versatile WordPress theme for
                        educational purpose, showcasing universities,
                        course, secondary school etc.
                    </p>
                    <div class="social">
                        <div class="facebook">

                        </div>
                        <!-- /.facebook -->
                        <div class="twitter">

                        </div>
                        <!-- /.twitter -->
                        <div class="intagram">

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
                        <div class=" send rounded-circle "></div>
                    </div>
                    <!-- /.square -->
                    <h5 class="mt-4 text-end">Search categories</h5>

                    <div class="box d-flex flex-wrap justify-content-end text-uppercase">
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
    padding: 1rem 2rem;
}

.send {
    position: absolute;
    top: 0;
    right: -20px;
    width: 60px;
    height: 60px;
    background-color: #E9D758;
}

.faculties {
    padding: 2px 6px;
    border: 1px solid white;
    margin: 0.50rem;
}
</style>