<script>
import Hero from "./Hero.vue";
import Banner from "./Banner.vue";
import WorkingProcess from "./WorkingProcess.vue";
export default {
    name: "PageMain",
    components: {
        Hero,
        Banner,
        WorkingProcess
    }
}
</script>

<template>
<Hero></Hero>
<Banner></Banner>
<WorkingProcess></WorkingProcess>
</template>

<style scoped lang="scss">
</style>