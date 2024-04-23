<script>
export default {
    name: "Hero",
}
</script>

<template>
<div class="container-fluid position-relative">
    <div class="row justify-content-center">
        <div class="col-4 px-5">
            <h1>Devotion that Never <strong>ends</strong></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi dolorem</p>
            <button>Read More</button>
        </div>
        <div class="col-4">
            <div class="img-container position-relative">
                <div class="d-flex px-4">
                    <div class="woman">
                        <img src="../assets/img/h-2-slider-img-15.png" alt="">
                    </div>
                    <div class="man">
                        <img src="../assets/img/h-2-slider-img-16.png" alt="">
                    </div>
                </div>
                    <div class="icons icon-bottom position-absolute">
                    <img src="../assets/img/h-2-slider-img-13.png" alt="">
                </div>
                <div class="icons icon-center position-absolute">
                    <img src="../assets/img/h-2-slider-img-12.png" alt="">
                </div>
                <div class="icons icon-top position-absolute">
                    <img src="../assets/img/h-2-slider-img-12.png" alt="">
                </div>
                <div class="icons top-right position-absolute">
                    <img src="../assets/img/h-2-slider-img-14.png" alt="">
                </div>
                <div class="icons center-right position-absolute">
                    <img src="../assets/img/short-slider-rev-1-img-6.png" alt="">
                </div>
                <div class="icons position-absolute bottom-right">
                    <img src="../assets/img/h-2-slider-img-17.png" alt="">
                </div>

            </div>
        </div>
            <div class="circle circle-right  d-flex justify-content-center align-items-center position-absolute"><i class="fa-solid fa-chevron-right"></i></div>
            <div class="circle circle-left d-flex justify-content-center align-items-center position-absolute"><i class="fa-solid fa-chevron-left"></i></div>
        <div class="col-12 d-flex justify-content-center mt-4 gap-4">
            <div><i class="fa-solid fa-circle"></i></div>
            <div><i class="fa-solid fa-circle"></i></div>
            <div><i class="fa-solid fa-circle"></i></div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">

.container-fluid {
    margin-top:100px;
}
img {
    width: 100%;
    height: 100%;
}
.icons {
    width: 50px;
    height: 50px;
}
.icon-bottom {
    bottom: 0%;
    left: -0%;
}
.icon-center {
    top: 40%;
    left: -10%;
}
.icon-top{
    top: -15%;
    left:0%;
}

.top-right{
    right: 14%;
    top: -20%;
}

.center-right{
    right: 7%;
    top: 18%;
}

.bottom-right{
    right: -2%;
    bottom: 0;
}

i {
    font-size: 8px;
}

.circle {
    height: 30px;
    width: 30px;
    border-radius: 50%;
    background-color: rgb(135, 135, 135);
}

.circle-right {
    top: 35%;
    right: 1%;
}

.circle-left{
    top: 35%;
    left: 1%;
}
h1 {
    font-size: 50px;
}

</style>