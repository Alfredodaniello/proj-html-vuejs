<script>
export default {
    name: "Banner",
}
</script>

<template>
<div class="container-fluid mt-3">
    <div class="row">
        <div class="col d-flex flex-wrap text-center">
            <div class="square">
                <img src="../assets/img/h-2-port-img-1.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-2.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-3.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-4.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-5.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-6.jpg" alt="">
            </div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
.square {
    width: calc(100% / 3);
    height: 451.73px;
    img {
        width: 100%;
        height: 100%;
    }
}

.container-fluid {
    padding-left: 0px !important;
    padding-right: 0px !important;
}
</style>