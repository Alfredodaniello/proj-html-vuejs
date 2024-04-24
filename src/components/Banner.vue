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
            <div class="square position-relative">
                <div class="little-square-bot position-absolute d-flex justify-content-center align-items-center">
                    <img src="../assets/img/svg-6.svg" alt="">
                </div>
                <div class="little-square position-absolute d-flex justify-content-center align-items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 87 87" style="height:55%" fill="#ffffff"><path d="M55.4 81.5c6.1-11.1 5.2-16.1-4.3-24.3 6.1-3.5 9.5-8.5 9.1-15.7-.5-8.2-7.7-14.7-16.3-14.6-8.5.1-15.6 6.7-15.9 15-.3 8.5 5.9 15.8 14.3 16.6 1.4.1 2.8.2 4.2.5 5.9 1.2 10.2 6.7 9.8 12.6-.4 6.4-5.5 11.4-11.8 11.7-19.6.9-38.6-14.8-41.3-34C-.1 26.9 14.4 6.8 36.4 2.8c22.3-4 43.4 10 48.1 32 4.3 20-8.6 41.2-28.4 46.7h-.7z"/></svg>
                </div>
                <img src="../assets/img/h-2-port-img-3.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-4.jpg" alt="">
            </div>
            <div class="square">
                <img src="../assets/img/h-2-port-img-5.jpg" alt="">
            </div>
            <div class="square position-relative">
                <div class="little-square-1 position-absolute d-flex justify-content-center align-items-center">
                    <i class="fa-solid fa-arrow-up"></i>
                </div>
                <div class="little-square-bot-1 position-absolute d-flex justify-content-center align-items-center">
                    <i class="fa-solid fa-arrow-up"></i>
                </div>
                <img src="../assets/img/h-2-port-img-6.jpg" alt="">
            </div>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/generic" as *;
@use "../style/partials/variables" as *;
.square {
    width: calc(100% / 3);
    height: calc(100vw / 3);
    img {
        width: 100%;
        height: 100%;
    }
}

.container-fluid{
    padding: 0; }
    .row {
        --bs-gutter-x: 0rem;
    }
.little-square {
    cursor: pointer;
    
    background-color: $brand-tertiary;
    right: 0;
    top: 17%;
    width: 30px;
    height: 30px;
    width: calc(100% / 15);
    height: calc(100vw / 48);
    }

.little-square-bot {
    background-color: white;
    cursor: pointer;
    right: 0;
    top: 25%;
    width: calc(100% / 15);
    height: calc(100vw / 48);
    img {
        width: 40%;
    }
}
.little-square-1 {
    cursor: pointer;
    
    background-color: $brand-quartiary;
    right: 0;
    top: 0%;
    width: 30px;
    height: 30px;
    width: calc(100% / 15);
    height: calc(100vw / 48);
    i{
        color: white;
    }
}


.little-square-2 {
    cursor: pointer;
    
    background-color: $brand-quartiary;
    right: 0;
    top: 0%;
    width: 30px;
    height: 30px;
    width: calc(100% / 15);
    height: calc(100vw / 48);
    i{
        color: white;
        font-size: 15;
    }
}

.little-square-bot-1 {
    background-color: $brand-quartiary;
    cursor: pointer;
    right: 0;
    bottom: 4%;
    width: calc(100% / 15);
    height: calc(100vw / 48);
    i{
        color: white;
    }
}

.fa-arrow-up{
    font-size: 75%;
}

</style>