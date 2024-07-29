<script>
export default {
    
}
</script>
<template >
    <div>
        <div class="wrap bg-dark">
         <div class="container">
            <div class="row">
                <div class="col-12 p-5">
                <p class="text-light">Content goes here</p>
                </div>
            </div>
        </div>
    </div>
    <div class="bg-lightblue p-5">
        <div class="container">
            <div class="row justify-content-evenly text-light p-0 m-0">
                <div class="col-2">
                    <div class="content">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <p class="d-inline-block">DIGITAL COMICS</p>
                    </div>
                </div>
                <div class="col-2">
                    <div class="content">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <p class="d-inline-block">DC MERCHANDISE</p>
                    </div>
                </div>
                <div class="col-2">
                    <div class="content">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <p class="d-inline-block">SUBSCRIPTION</p>
                    </div>
                </div>
                <div class="col-2">
                    <div class="content">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <p class="d-inline-block">COMIC SHOP LOCATOR</p>
                    </div>
                </div>
                <div class="col-2">
                    <div class="content">
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

.bg-lightblue{
        background-color: variables.$primary_color;

     .col-2{
        padding: 0px;
        margin: 0px;
        align-content: center;
        align-self: center;

        img {
        max-width: 60px;
        max-height: 60px;
        margin-right: 5px;
    }
    }
    }
</style>