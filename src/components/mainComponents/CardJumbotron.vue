<script>
export default {
    name: "CardJumbotron",
    props: {
        active: Number
    },
    data() {
        return {

        }
    },

    mounted() {


    }
}


</script>

<template>

    <div v-if="active == 0">
        <h1 class="titleCards">We are Everlead<i class="fa-solid fa-circle" style="color: #ff4612;"></i></h1>
        <p style="width: 50%;">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem at perferendis
            culpa pariatur aperiam
            corrupti blanditiis, fugit dolo.</p>
        <a href="#" class="btn btn-white btn-lg bg-white me-3 p-3" data-mdb-ripple-init role="button"
            aria-pressed="true">READ MORE <span class="lineVertical "></span> <span class="arrow ms-2">⟶</span></a>
        <a href="#" class="orange btn btn-lg p-3 text-white" data-mdb-ripple-init role="button"
            aria-pressed="true">PURCHASE <span class="lineVertical"></span> <span class="arrow ms-2">⟶</span></a>
    </div>

    <div v-if="active == 1">
        <h1 class="titleCards">Help you achieve</h1>
        <h1 class="titleCards">anithing<i class="fa-solid fa-circle" style="color: #ff4612;"></i></h1>
        <a href="#" class="btn btn-white btn-lg bg-white me-3 p-3" data-mdb-ripple-init role="button"
            aria-pressed="true">READ MORE <span class="lineVertical "></span> <span class="arrow ms-2">⟶</span></a>
        <a href="#" class="orange btn btn-lg p-3 text-white" data-mdb-ripple-init role="button"
            aria-pressed="true">PURCHASE <span class="lineVertical"></span> <span class="arrow ms-2">⟶</span></a>
    </div>

    <div v-if="active == 2">
        <h1 class="titleCards">Our Team<i class="fa-solid fa-circle" style="color: #ff4612;"></i></h1>
        <a href="#" class="btn btn-white btn-lg bg-white me-3 p-3" data-mdb-ripple-init role="button"
            aria-pressed="true">READ MORE <span class="lineVertical "></span> <span class="arrow ms-2">⟶</span></a>
        <a href="#" class="orange btn btn-lg p-3 text-white" data-mdb-ripple-init role="button"
            aria-pressed="true">PURCHASE <span class="lineVertical"></span> <span class="arrow ms-2">⟶</span></a>
    </div>




</template>

<style scoped>
.lineVertical {
    margin-left: 2rem;
    height: 100%;
    border-left: 1px solid;
}

.orange {
    background-color: #FF4612;

}

.titleCards {
    font-family: "Libre Baskerville", serif;
    font-weight: 700;
    font-style: normal;
    font-size: 85px;
}

.fa-circle {
    font-size: 15px;
}
</style>