<script>
export default {
    name: "Calendar",
}
</script>

<template>
<div class="container">
    <div class="row justify-content-center mt-5 mb-5">
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center">
                <div>07</div>
                <small>May 19</small>
            </div>
            <img src="../assets/img/h-2-blog-img-1.jpg" alt="">
            <h6>This way, loves: a detailed guide trough new design</h6>
            <span>by Emily Fields</span>
        </div>
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center">
                <div>07</div>
                <small>May 19</small>
            </div>
            <img src="../assets/img/h-2-blog-img-2.jpg" alt="">
            <h6>I try to give people a different way to looking art</h6>
            <span>by Emily Fields</span>        
        </div>
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center">
                <div>07</div>
                <small>May 19</small>
            </div>
            <img src="../assets/img/h-2-blog-img-3.jpg" alt="">
            <h6>This way, loves: a detailed guide trough new design</h6>
            <span>by Emily Fields</span>       
        </div>    
    </div>
</div>
</template>
<style scoped lang="scss">
.img-container {
        height: 30%;
    }
    img {
        width: 100%;
        height: 100%;
    }
.square{
    width: 20%;
    height: 25%;
    border: 1px black solid;
    left: 10%;
    top: -5%;
}


</style>