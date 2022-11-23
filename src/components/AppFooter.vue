<script>
import Networking from "../assets/js/Networking";
import link from "../assets/js/link";
export default {
    name: 'AppFooter',
    // components: {
    //     link,
    //     items
    // },
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
            <div class="row text-white">
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
                    <h5 class="text-center">Get EduPrime</h5>
                    <ul>
                        <li v-for="item in link">
                            {{ item.text }}
                        </li>
                    </ul>
                </div>
                <!-- /.col -->
                <div class="col-3">
                    <h5>Networking</h5>
                    <ul>
                        <li v-for="item in Networking">
                            {{ item.text }}
                        </li>
                    </ul>
                </div>
                <!-- /.col -->
                <div class="col-3">
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim, itaque molestiae ad quidem
                        nihil, nemo reiciendis deserunt earum quam beatae dolor doloribus explicabo nostrum maxime ipsum
                        magnam aut. Velit, nostrum!
                    </p>
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
</style>