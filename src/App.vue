<script >
import PageHeader from "./components/PageHeader.vue";
import PageMain from "./components/PageMain.vue";
import Hero from "./components/Hero.vue";
export default {
  name: "App",
  components: {
    PageHeader,
    PageMain,
    Hero
  },
  data (){
    return {
      sections: [
      {name:"HOME"},
      {name:"PAGES"},
      {name:"PORTFOLIO"},
      {name:"BLOG"},
      {name:"SHOP"},
      {name:"ELEMENTS"},
      ],
      images: 
        { 
          logoUrl:"../assets/img/logo-sidearea-1.png",
          imageUrl: "../assets/img/svg-1.svg"
        }
    }
  }
}
</script>

<template>
<div>
  <header>
    <PageHeader :info="sections" :images="images"></PageHeader>
  </header>

  <main>
<PageMain></PageMain>
  </main>
</div>
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;
</style>
