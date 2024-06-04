<script>

export default {
    name: "MyAppHeader",
    data() {
        return {
        }
    },
    methods: {
    },
    mounted() {
    }
}
</script>

<template>
    <!-- CONTAINER PRINCIPALE CON SFONDO -->
    <div class="fluid bgHeader">
        <!-- NAVBAR -->
        <nav class="navbar navbar-light bg-trasparent p-5">
            <div class="containerNav d-flex">
                <!-- LOGO NAV -->
                <div>
                    <a class="navbar-brand" href="#">
                        <img src="../assets/img/logo-img-01.png" width="25" height="25" class="logoHeader align-top">

                    </a>
                </div>

                <!-- DROPDOWN LINK NAV -->
                <div class="dropdown d-flex">


                    <div class="text-dark">⟶</div>
                    <div class="dropdown">
                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>


                    <div class="text-dark">⟶</div>
                    <div class="dropdown">
                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>


                    <div class="text-dark">⟶</div>
                    <div class="dropdown">
                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>

                    <div class="text-dark">⟶</div>
                    <div class="dropdown">

                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>

                    <div class="text-dark">⟶</div>
                    <div class="dropdown">

                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>

                    <div class="text-dark arrow">⟶</div>
                    <div class="dropdown">

                        <a class="dropdown-item pe-4 text-dark fw-bold" href="#" id="dropdownHomes"
                            data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            HOMES
                        </a>

                        <div class="dropdown-menu" aria-labelledby="dropdownHomes">
                            <a class="dropdown-item" href="#">Action</a>
                            <a class="dropdown-item" href="#">Another action</a>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </div>

                    <a class="dropdown-item pe-4 text-dark fw-bold" href="#">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </a>

                    <a class="dropdown-item pe-3 text-dark fw-bold" href="#">
                        <i class="fa-solid fa-bars"></i>
                    </a>

                </div>

            </div>
        </nav>

        <div  class="container cardHeader">
            <div>
            <h1>OUR TEAM</h1>
            <p style="width: 50%;">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem at perferendis culpa pariatur aperiam
                corrupti blanditiis, fugit dolo.</p>
                <a href="#" class="btn btn-primary btn-lg active me-3" data-mdb-ripple-init role="button" aria-pressed="true">Primary link</a>
                <a href="#" class="btn btn-primary btn-lg active" data-mdb-ripple-init role="button" aria-pressed="true">Primary link</a>
            </div>
        </div>
    </div>

</template>

<style scoped>
.containerNav {
    margin-left: 2rem;
    width: 100%;
    justify-content: space-between;
    flex-wrap: inherit;
    align-items: center;
}

.bgHeader {
    height: 100vh;
    background-image: url(../assets/img/rev-slider-main-home-img-02.png);
}

.logoHeader {
    width: 100%;

}

.cardHeader {
    color: black;
    display: flex;
    justify-content: start;
    flex-wrap: wrap;
    height: 60%;
    align-items: center;

}
</style>
