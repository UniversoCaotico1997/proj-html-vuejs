<script>
export default {
    name: 'SectionUniversity'
}
</script>

<template>
    <section class="university">
        <div class="container">

            <div class="logo d-flex justify-content-center align-items-center pt-5">
                <img src="../assets/img/Clock-and-Bell.png" width="50px" alt="">
            </div>
            <!-- /.logo -->

            <!-- title -->
            <h1 class=" text-white text-center my-4">University Year</h1>
            <!-- /.title -->

            <div class="time_line position-relative">


                <div class="description_classes text-center text-white">
                    <h6>Demo Classes </h6>
                    <p>In the first week, students try to accomodate with the
                        <br> teaching style and choose their optional courses.
                    </p>
                </div>
                <!-- /.description_classes -->

                <div class="description_day text-center text-white">
                    <h6>Graduation Day</h6>
                    <p>On the day of graduation, all students gather for the
                        <br> ceremony and the network and party among others.
                    </p>
                </div>
                <!-- /.description_day -->

                <div class="img_line ">
                    <img src="../assets/img/Timeline-Item.png" alt="">
                </div>
                <!-- /.img_lime -->

                <div class="description_orientation text-center text-white">
                    <h6>Orientation</h6>
                    <p>First day of the university Year, all student gather for
                        <br> the opening ceremony and then network with others.
                    </p>
                </div>
                <!-- /.description_orientation -->

                <div class="description_evaluation text-center text-white">
                    <h6>Evaluation</h6>
                    <p>At the end of a semester, students take a general
                        <br> evalutation test forevery subject they're learning
                    </p>
                </div>
                <!-- /.description_evaluation -->
            </div>
            <!-- /.time_line -->
        </div>
        <!-- /.container -->
    </section>

    <section class="events">


    </section>

</template>

<style lang="scss" scoped>
.container {
    width: 70%;
}

h1 {
    background-color: #DB2A2C;
}

.time_line {
    padding: 8rem;
}

.description_classes {
    position: absolute;
    top: 60px;
    left: 290px;
}

.description_day {
    position: absolute;
    top: 60px;
    right: 140px;
}

.description_orientation {
    position: absolute;
    bottom: 40px;
    left: 140px;
}

.description_evaluation {
    position: absolute;
    bottom: 40px;
    right: 290px;
}

p {
    font-size: x-small;
}
</style>
