<script>
export default {
    name: 'Events'
}
</script>


<template>
    <section class="events pb-5">
        <div class="container">
            <div class="logo d-flex justify-content-center align-items-center pt-5">
                <img src="../assets/img/upcoming-events-calendar-icon.png" alt="">
            </div>
            <!-- /.logo -->
            <!-- title -->
            <h2 class=" text-white text-center my-5">Upcoming Events</h2>
            <!-- /.title -->
            <div class="coaching_session d-flex gap-5">
                <div class="first_session bg-white text-center px-2 rounded position-relative">
                    <h5 class="pt-4">Coaching Session</h5>
                    <small>20 May 21:30 PM</small>
                    <p class="mb-5">Lorem ipsum dolor sit amet consectetur.
                        Aspernatur, a!
                    </p>
                    <a class="button more rounded-pill position-absolute top-100 start-50 translate-middle"
                        href="#">Find More</a>
                </div>
                <!-- /.first_session -->
                <div class="second_session bg-white text-center px-2 rounded position-relative">
                    <h5 class="pt-4">Coaching Session</h5>
                    <small>24 Mar 18:00 PM</small>
                    <p class="mb-5">Lorem ipsum dolor sit amet consectetur.
                        Aspernatur, a!
                    </p>
                    <a class="button more rounded-pill position-absolute top-100 start-50 translate-middle"
                        href="#">Find More</a>
                </div>
                <!-- /.second_session -->
                <div class="third_session bg-white text-center px-2 rounded position-relative">
                    <h5 class="pt-4">Coaching Session</h5>
                    <small>12 Feb 13:30 PM</small>
                    <p class="mb-5">Lorem ipsum dolor sit amet consectetur.
                        Aspernatur, a!
                    </p>
                    <a class="button more rounded-pill position-absolute top-100 start-50 translate-middle"
                        href="#">Find More</a>
                </div>
                <!-- /.third_session -->
            </div>
            <!-- /.coaching_session -->

            <!-- button -->
            <div class=" my-5 text-center">
                <a class="button view rounded-pill" href="#">View all Events </a>
            </div>
            <!--/. button -->
        </div>
        <!-- /.container -->
    </section>
</template>

<style lang="scss" scoped>
@use'../../src/assets/partial/container';

img {
    width: 80px;
}

.button {
    padding: 0.75rem 1rem;
    text-decoration: none;
    color: white;
}

.more {
    background-color: #DB2A2C;
}

.view {
    background-color: #E9D758;
}
</style>