<template>
    <div class="site_main">
        <div class="conteiner">
            <p>Content goes here</p>
        </div> 
        <div class="content">
            <div class="card">
                <img class="img_card" src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="card">
                <img class="img_card" src="../assets/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDASE</p>
            </div>
            <div class="card">
                <img class="img_card" src="../assets/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p>
            </div>
            <div class="card">
                <img class="img_card" src="../assets/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </div>
            <div class="card">
                <img class="img_card" src="../assets/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </div>

        </div>
    </div>
</template>

<script>
export default {
  name: 'SiteMain',
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Cantarell&display=swap');
.conteiner{
    height: 100px;
    width: 100%;
    background-color: rgba(28, 28, 28, 1);
    display: flex;
    align-items: center;
    p{
        color: white;
        font-size: 20px;
          margin: 300px;
    }
}
.content {
    width: 100%;
    background-color: rgba(2, 130, 249, 1);
    display: flex;
    justify-content: center;
    .card{
        display: flex;
        align-items: center;
        padding: 2rem;
        
    }
    .img_card{
        width: 40px;
        margin-right: 10px;
    }
    p {
        color: white;
        font-size: 12px;
        font-family: 'Cantarell', sans-serif;
    }
}


</style>