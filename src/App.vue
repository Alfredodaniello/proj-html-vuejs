<script >
import PageHeader from "./components/PageHeader.vue";
export default {
  name: "App",
  components: {
    PageHeader
  }
}
</script>

<template>
<div>
  <header>
    <PageHeader></PageHeader>
  </header>
  
</div>
</template>

<style lang="scss">
@use "./style/partials/generic" as *;
@use "./style/partials/variables" as *;
</style>
