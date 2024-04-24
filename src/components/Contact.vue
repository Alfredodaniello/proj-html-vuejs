<script>
export default {
    name: "Contact",
}
</script>

<template>
<div class="container-fluid ms-container">
    <div class="row">
        <div class="col-10 m-auto text-center div-container">
            <h1>Want to work with us? Send us <strong>a message</strong>!</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad alias veritatis non facere quia accusantium, tenetur eligendi sequi perspiciatis repudiandae fugiat laborum! Vitae rerum hic ipsa suscipit, aut atque eveniet.</p>
            <button>Contact</button>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use "../style/partials/generic" as *;
@use "../style/partials/variables" as *;

.ms-container {
    height:300px;
    background-image: url("../assets/img/h-2-background-1.jpg");
    object-fit: auto;
}
button  {
    letter-spacing: 2px;
    font-weight: 400;
    font-size: 15px;
    padding: 7px 30px;
    border: $brand-quartiary ;
background-color: $brand-quartiary;
}

h1 {
    margin-top: 70px;
}

P {
    color: $brand-secondary;
}

button:hover {
    color: white;
    background-color: $brand-primary;
}
</style>