<script>
import comics from '../data/dc-comics.json';
export default {
    data() {
        return {
            comics
        }
    }

}
</script>
<template>
    <div class="bg-cartoon">

    </div>
    <div>
        <div class="wrap bg-dark">
            <div class="container">
                <div class="row">
                    <div class="col-12 p-5 d-flex flex-wrap justify-content-center">
                        <div v-for="(comic, index) in comics" :key="index" class="col-6 col-md-4 col-lg-2 mb-4 d-flex">
                            <div class="card bg-transparent w-100 mx-3">
                                <img :src="comic.thumb" :alt="comic.series" class="card-img-top img-fluid">
                                <div>
                                    <h5 class="text-white text-center">{{ comic.series }}</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="wrap bg-lightblue p-5">
            <div class="container">
                <div class="row text-light p-0 m-0 row-col-5">
                    <div class="col">
                        <div class="content text-center">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <p class="d-inline-block">DIGITAL COMICS</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="content text-center">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                            <p class="d-inline-block">DC MERCHANDISE</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="content text-center">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                            <p class="d-inline-block">SUBSCRIPTION</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="content text-center">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                            <p class="d-inline-block">COMIC SHOP LOCATOR</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="content text-center">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                            <p class="d-inline-block">DC POWER VISA</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss">
@use '../styles/partials/variables';

.bg-cartoon {
    background-image: url('../assets/img/jumbotron.jpg');
    height: 450px;
    background-size: cover;
}

.card {
    border: none;

    img {
        width: 200px;
        height: 250px;
    }
}

.bg-lightblue {
    background-color: variables.$primary_color;

    .col {
        padding: 0px;
        margin: 0px;
        align-content: center;
        align-self: center;


        p {
            padding-left: 0px;
        }

        img {
            max-width: 70px;
            max-height: 70px;
            margin-right: 5px;
        }
    }
}
</style>