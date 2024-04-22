<script>
export default {
    name: "PageHeader",
    props: ["info", "images"],
    methods: {
        //Funzione per stampare l'immagine dinamicamente
        getImgByUrl: function(relative) {
            return new URL(relative, import.meta.url).href;
        }
    }
}
  

</script>

<template>
<div class="ms-header d-flex px-3 justify-content-between align-items-center">
    <div class="logo">
        <img :src=getImgByUrl(images.logoUrl) alt="logo">
    </div>
    <nav>
        <ul class="d-flex gap-4 mb-0">
            <li v-for="section in info" class="sections">{{ section.name }}</li>
            <li>
                <img :src="getImgByUrl(images.imageUrl)" alt="logo">
            </li>
        </ul>
    </nav>
</div>
</template>

<style scoped lang="scss">
.ms-header {
    height: 70px;
}

.logo {
    width: 80px;
    height: 30px;
    img {
        width: 100%;
        height: 100%;
    }
}
@media screen and (max-width: 768px) {
    .sections{
        display: none;
    }
}
</style>