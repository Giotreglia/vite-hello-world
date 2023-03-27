<script>
export default {
    name: "AppHeroBonus"
}
</script>

<template>
    <div class="hero-wrapper">

        <div class="hero-container">

            <video autoplay loop id="myVideo">
                <source src="/jumbovideo.mp4" type="video/mp4">
            </video>
            <h2 id="secondary-claim">Vieni a scoprire anche tu le bellezze di Vite!</h2>
            <h1 id="main-claim">Parti subito!</h1>


        </div>

    </div>
</template>

<style scoped>
.hero-wrapper {
    width: 100vw;
    border: solid 8px black;
    height: 600px;
    display: flex;
    justify-content: flex-end;
    padding: 0 30px;
    position: relative;
    overflow: hidden;
}

#myVideo {
    object-fit: cover;
    position: absolute;
    top: -400px;
    left: 0;
    z-index: -1;
}

.hero-container {
    display: flex;
    max-width: 100%;
    justify-content: space-between;
    flex-direction: column;
    padding-top: 200px;
}

#main-claim {
    font-size: 110px;
    text-align: right;
    color: rgba(250, 235, 215, 0.95);
    line-height: 130px;

}

#secondary-claim {
    font-size: 40px;
    line-height: 40px;
    text-align: right;
    color: white;
}

@media all and (min-width: 625px) {
    .hero-container {
        padding-top: 200px;
    }

    #main-claim {
        font-size: 130px;
        line-height: 130px;
    }
}

@media all and (min-width: 760px) {
    .hero-container {
        padding-top: 350px;
    }

    #main-claim {
        font-size: 130px;
        line-height: 130px;
    }
}

@media all and (min-width: 1200px) {
    #main-claim {
        font-size: 180px;
        line-height: 180px;
    }

    .hero-container {
        padding-top: 350px;
    }
}

@media all and (min-width: 1768px) {}
</style>