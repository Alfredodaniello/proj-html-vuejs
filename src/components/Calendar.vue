<script>
export default {
    name: "Calendar",
}
</script>

<template>
<div class="container">
    <div class="row justify-content-center mt-5 mb-5">
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center d-flex justify-content-center align-items-center">
                <div>07</div>
            </div>
            <img src="../assets/img/h-2-blog-img-1.jpg" alt="">
            <h6 class="mt-1">This way, loves: a detailed guide trough new design</h6>
            <span>by Emily Fields</span>
        </div>
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center d-flex justify-content-center align-items-center">
                <div>07</div>  
            </div>
            <img src="../assets/img/h-2-blog-img-2.jpg" alt="">
            <h6 class="mt-1">I try to give people a different way to looking art</h6>
            <span>by Emily Fields</span>        
        </div>
        <div class="col-lg-3 col-md-6 mt-md-4 mt-sm-5 img-container position-relative">
            <div class="square position-absolute text-center d-flex justify-content-center align-items-center">
                <div>07</div>
            </div>
            <img src="../assets/img/h-2-blog-img-3.jpg" alt="">
            <h6 class="mt-1">This way, loves: a detailed guide trough new design</h6>
            <span>by Emily Fields</span>       
        </div>    
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/generic" as *;
@use "../style/partials/variables" as *;
.img-container {
        height: 30%;
    }
    img {
        width: 100%;
        height: 100%;
    }
.square{
    background-color: $brand-quartiary;
    width: 15%;
    height: 15%;
    left: 10%;
    top: -5%;
    div {
        font-style: italic;
        font-weight: 1000;
    }
}

span {
    font-size: 14px;
    font-style: italic;
}


</style>