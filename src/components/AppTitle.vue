<script>
export default {
    name: "AppTitle"
}
</script>

<template>
    <div class="header-wrapper">
        <h1>La mia prima app con Vite!</h1>
    </div>
</template>

<style scoped>
.header-wrapper {
    height: 120px;
    padding: 0px 0 0 10px;
}

h1 {
    text-align: left;
    font-size: 42px;
    color: black;

}

@media all and (min-width: 480px) {

    h1 {
        font-size: 50px;
    }

    .header-wrapper {
        height: 140px;
        padding: 0px 0 0 10px;
    }

}

@media all and (min-width: 576px) {

    h1 {
        font-size: 50px;
    }

    .header-wrapper {
        height: 140px;
        padding: 30px 0 0 10px;
    }

}

@media all and (min-width: 792px) {

    h1 {
        font-size: 60px;
    }

    .header-wrapper {
        height: 150px;
        padding: 25px 0 0 10px;
    }
}



@media all and (min-width: 992px) {
    h1 {
        font-size: 90px;
    }

    .header-wrapper {
        height: 150px;
        padding: 25px 0 0 10px;
    }
}
</style>