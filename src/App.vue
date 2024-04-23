<script >
import PageHeader from "./components/PageHeader.vue";
import PageMain from "./components/PageMain.vue";
import Hero from "./components/Hero.vue";
import Banner from "./components/Banner.vue";
import WorkingProcess from "./components/WorkingProcess.vue";
import PageFooter from "./components/PageFooter.vue";
export default {
  name: "App",
  components: {
    PageHeader,
    PageMain,
    Hero,
    Banner,
    WorkingProcess,
    PageFooter
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
        },
      footer: {
        logoUrl: "../assets/img/logo-sidearea-1.png",
        subtitle: "Let's get creative",
        email: "mare.qode@gmail.com",
        number: "+56456 039 328",
        address: "Avenue D'Aunghem, 10",
        country: "1040 Brussels, Belgium",
        contacts: "Stay in touch with us"
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

  <footer>
    <PageFooter :infoFooter="footer"></PageFooter>
  </footer>
</div>
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;
</style>
