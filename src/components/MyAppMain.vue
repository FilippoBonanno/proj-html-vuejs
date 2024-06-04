<script>
import store from "../data/store.js";
import Achievements from "./mainComponents/Achievements.vue";
import Bigvideo from "./mainComponents/Bigvideo.vue";
import Contacts from "./mainComponents/Contacts.vue";
import Events from "./mainComponents/Events.vue";
import Founder from "./mainComponents/Founder.vue";
import News from "./mainComponents/News.vue";
import Plans from "./mainComponents/Plans.vue";
import Specialties from "./mainComponents/Specialties.vue";
import Staff from "./mainComponents/Staff.vue";
import Stats from "./mainComponents/Stats.vue";
import Testimonials from "./mainComponents/Testimonials.vue";
export default {
    name: "MyAppMain",
    components: {
        Achievements,
        Bigvideo,
        Contacts,
        Events,
        Founder,
        News,
        Plans,
        Specialties,
        Staff,
        Stats,
        Testimonials
    },
    data() {
        return {
            store
        }
    },
    methods: {
        getImg(path,name){
            return new URL(`${path}${name}`,import.meta.url).href;
        }
    },
    mounted() {
    }
}
</script>

<template>
    <h1>Questo è il main</h1>

    
    <Specialties :cardInfo="store.immagini.skillsIcon"/>
    <Founder />
    <Events />
    <Stats />
    <News />
    <Testimonials />
    <Bigvideo />
    <Achievements />
    <Staff />
    <Contacts />
    <Plans />

</template>

<style scoped></style>
