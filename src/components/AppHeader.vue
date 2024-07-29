<script>
export default {
    
}
</script>
<template >
    <div class="container">
        <div class="row">
            <div class="col-4 my-3">
            <img src="../assets/img/dc-logo.png" alt="">
       </div>
        <div class="col-8 align-self-center my-3">
         <div class="content">
             <ul class="list-unstyled d-flex fw-bold">
                    <li> 
                        <a href="#">CHARACTERS</a>
                    </li>
                    <li>
                        <a href="#">COMICS</a>
                    </li>
                    <li>
                        <a href="#">MOVIES</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">GAMES</a>
                    </li>
                    <li>
                        <a href="#">COLLECTIBLES</a>
                    </li>
                    <li>
                        <a href="#">VIDEOS</a>
                    </li>
                    <li>
                        <a href="#">FANS</a>
                    </li>
                    <li>
                        <a href="#">NEWS</a>
                    </li>
                    <li>
                        <a href="#">SHOP</a>
                    </li>
             </ul>
         </div>
     </div>
 </div>
   </div>
</template>
<style lang="scss">
@use '../styles/partials/variables';
    li{
        margin-right: 30px;

        a {
        text-decoration: none;
        color: black;
        padding-bottom: 50px;

        &:hover {
            color: variables.$primary_color;
            border-bottom: 5px solid variables.$primary_color;
        }
        }
    }
</style>