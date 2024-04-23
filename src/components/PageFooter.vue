<script>
export default {
    name: "PageFooter",
    props: ["infoFooter"],
    methods: {
        //Funzione per stampare l'immagine dinamicamente
        getImgByUrl: function(relative) {
            return new URL(relative, import.meta.url).href;
        }
    }
}
</script>

<template>
<div class="container-fluid">
    <div class="row justify-content-center align-items-center h-100">
        <div class="col-lg-2 col-md-5">
            <div class="mb-2 mt-sm-3">
                <img :src="getImgByUrl(infoFooter.logoUrl)" alt="">
            </div>
            <div>{{infoFooter.subtitle}}</div>
        </div>
        <div class="col-lg-2 col-md-5">
            <div class="mb-2">{{ infoFooter.email }}</div>
            <div>{{infoFooter.number}}</div>
        </div>
        <div class="col-lg-2 col-md-5">
            <div class="mb-2">{{infoFooter.address}}</div>
            <div>{{infoFooter.country}}</div>
        </div>
        <div class="col-lg-2 col-md-5">
            <div class="mb-2">{{infoFooter.contacts}}</div>
            <div class="d-flex gap-4 icons">
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-pinterest-p"></i>
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-linkedin-in"></i>
            </div>
        </div>
    </div>
    
</div>
</template>

<style scoped lang="scss">
.container-fluid {
    height: 120px;
    background-color: #c0e1cf;
}

@media screen and (max-width: 768px){
    .container-fluid {
        height: 350px;
        text-align: center;
    }
}

@media screen and (min-width: 768px) and (max-width: 992px){
    .container-fluid {
        height: 180px;
        text-align: center;
    }

}
</style>