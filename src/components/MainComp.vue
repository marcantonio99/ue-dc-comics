<template>
    <main>
        <section id="products">
            <div>
                <h2>Content goes here</h2>
            </div>
        </section>
        <section id="dc-images">
            <div class="images-flex">
                <div>
                <img class="img-svg" src="../assets/img/buy-dc-power-visa.svg" alt="visa">
                <span>DC POWER VISA</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital">
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="merch">
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="sub">
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shoplocator">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            </div>
        </section>
    </main>
</template>

<script>
    export default {
        name: 'MainComp'
    }
</script>

<style lang="scss" scoped>
#dc-images>div,
#products>div{
    margin: 0 auto;
    width: 80%;
}

#products{
    background-color: black;
    color: white;
    padding: 60px 0;
}

#dc-images{
    background-color: rgb(49, 126, 235);
    display: flex;
    align-content: center;
    justify-content: space-around;
    padding: 50px 0;

    div{
        display: flex;
        gap: 10px;
        align-items: center;
        color: white;
        font-weight: bold;
    }

    img{
    height: 50px;
    }
    .img-svg{
        width: 45px;
    }
    .images-flex{
        display: flex;
        justify-content: space-around;
        align-content: center;
    }
}
</style>