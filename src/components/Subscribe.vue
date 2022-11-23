<script>
export default {
    name: 'Subscribe'
}
</script>

<template>
    <div class="Subscribe">
        <div class="container">
            <div class="box  py-5 d-flex justify-content-between align-items-center">
                <div class="square">
                    <h3 class="text-white">Subscribe Now to Our Newsletter !</h3>
                </div>
                <!-- /.square -->
                <div class="square position-relative">
                    <input class="custom rounded-pill" type="text" placeholder="Email addres..">
                    <div class=" send rounded-circle "></div>
                </div>
                <!-- /.square -->
            </div>
            <!-- /.box -->

        </div>
        <!-- /.container -->
    </div>
</template>

<style lang="scss" scoped>
@use'../assets/partial/container';

.custom {
    padding: 1rem 6rem;
}

.send {
    position: absolute;
    top: 0;
    right: 1px;
    width: 60px;
    height: 60px;
    background-color: #E9D758;
}
</style>