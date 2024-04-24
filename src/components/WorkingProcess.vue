<script>
export default {
    name: "WorkingProcess",
}
</script>

<template>
<div class="container-fluid">
    <div class="row">
        <div class="col-9 m-auto text-center mt-5 mb-5 position-relative">
            <h1>Working <strong>process</strong></h1>
            <div class="line position-absolute">
                    <img src="../assets/img/svg-3.svg" alt="">
                </div>
            <div class="process d-flex justify-content-between mt-5 px-1">
                <div class="i-container d-flex flex-column align-items-center">
                    <div class="circle d-flex justify-content-center align-items-center"><i class="fa-solid fa-lightbulb"></i></div>
                    <h6>First theres an idea</h6>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, facere tempora aliquam incidun</p>
                </div>
                <div class="i-container d-flex flex-column align-items-center px-1">
                    <div class="circle d-flex justify-content-center align-items-center"><i class="fa-regular fa-comment"></i></div>
                    <h6>Then we talk about</h6>
                    <p>orem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, facere tempora aliquam incidun</p>
                </div>
                <div class="i-container d-flex flex-column align-items-center px-1">
                    <div class="circle d-flex justify-content-center align-items-center"><i class="fa-solid fa-cloud"></i></div>
                    <h6>And we think about</h6>
                    <p>orem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, facere tempora aliquam incidun</p>
                </div>
                <div class="i-container d-flex flex-column align-items-center px-1">
                    <div class="circle d-flex justify-content-center align-items-center"><i class="fa-solid fa-pen-clip"></i></div>
                    <h6>So we draw about</h6>
                    <p>orem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, facere tempora aliquam incidun</p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/generic" as *;
@use "../style/partials/variables" as *;
.circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background-color: antiquewhite;
}

.line {
    width: 78%;
    top: 25%;
    left: 10%;
    img {
        width: 100%;
    }
}

i {
    font-size: 30px;
}

.i-container{
    z-index: 99;
}
p {
    font-size: 14px;
}

.fa-lightbulb{
    color: $brand-quartiary
}

.fa-comment {
    color: $brand-icon-primary;
}

.fa-cloud {
    color: $brand-icon-secondary
}

.fa-pen-clip {
    color: $brand-icon-tertiary
}

p {
    color: $brand-secondary
}
</style>