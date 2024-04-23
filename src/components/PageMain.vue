<script>
import Hero from "./Hero.vue";
import Banner from "./Banner.vue";
import WorkingProcess from "./WorkingProcess.vue";
import Contact from "./Contact.vue";
import Calendar from "./Calendar.vue";
export default {
    name: "PageMain",
    components: {
        Hero,
        Banner,
        WorkingProcess,
        Contact,
        Calendar
    }
}
</script>

<template>
<Hero></Hero>
<Banner></Banner>
<WorkingProcess></WorkingProcess>
<Contact></Contact>
<Calendar></Calendar>
</template>

<style scoped lang="scss">
</style>