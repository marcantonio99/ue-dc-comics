<template>
    <footer>
        <div class="container">
            <div class="footer-lists">

               <div>
                <h3>DC COMICS</h3>
                <ul> 
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">News</a></li>
                </ul>

                <h3>SHOP</h3>
                <ul> 
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
                </ul>
               </div>

               <div>
                <h3>DC</h3>
                <ul> 
                    <li><a href="">Terms Of Use</a></li>
                    <li><a href="">Privacy policy(New)</a></li>
                    <li><a href="">Ad Choise</a></li>
                    <li><a href="">Adverting</a></li>
                    <li><a href="">Jobes</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent Workshop</a></li>
                    <li><a href="">CPSC Certificaces</a></li>
                    <li><a href="">Ratings</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contacts Us</a></li>
                </ul>
               </div>

               <div>
                <h3>SITES</h3>
                <ul> 
                    <li><a href="">DC</a></li>
                    <li><a href="">MAQ Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Visa</a></li>
                </ul>
               </div>

            </div>
            <div class="dc-logo-bg">
            </div>
        </div>

        <section id="footer-cta">
            <div class="container">
                <div class="btn">
                    Registrati
                </div>

                <div>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </section>
    </footer>
</template>

<script>
    export default {
        name: 'FooterComp'
    }
</script>

<style lang="scss" scoped>
 footer{
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    color: white;

    .container{
        margin: 0 auto;
        width: 80%;
        display: flex;
        justify-content: space-between;
    }

    .footer-list{
        padding: 30px 0;
        display: flex;
        gap: 10px;

        ul{
            font-size: 14px;
        }

    a{
        color: lightgray;
    }

    .dc-logo-bg{
        background-image: url('../assets/img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        width: 40%;
    }

    #footer-cta{
        background-color: black;
        padding: 30px 0;

        .btn{
            padding: 15px;
            border: 1px solid rgb(49, 126, 235);
        }

        .footer-social{
            display: flex;
            gap: 10px;
            align-items: center;
        }
    }
 }
}
</style>