<template>
    <div class="site_main">
        <div class="jumbo">
            <div class="targetta flex">CURRENT SERIES</div>
        </div>
        <div class="card_list flex">
            <div class="content_card flex">
                 <Product v-for="(card) in cards" :key="card.series" :image="card.thumb" :title="card.series"/>
            </div>
            <div class="button">
                     <button class="btn">LOAD MORE</button>
           </div>
        </div> 
        <div class="content flex">
            <div class="card flex">
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

import Product from "./Product.vue"

export default {
  data() {
      return{
       cards:   [
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    "price": "$4.99",
    "series": "Batman: White Knight Presents: Harley Quinn",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  },
]
      }
  },

  components: {
      Product,
  }
}

</script>

<style scoped lang="scss">
@import "../assets/style/variabili.scss";
@import "../assets/style/common.scss";

@import url('https://fonts.googleapis.com/css2?family=Cantarell&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:wght@700&display=swap');
.jumbo {
    width: 100%;
    height: 265px;
    background-image: url('../assets/jumbotron.jpg');
    background-size: cover;
    position: relative;
    .targetta{
    width: 131px;
    height: 32px;
    background-color: $dc_primary_color;
    position: absolute;
    left: 194px;
    top: 255px;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 15px;
    font-family: 'Open Sans Condensed', sans-serif;
    }
}
.card_list{
    width: 100%;
    background-color: rgba(28, 28, 28, 1);
    align-items: center;
    flex-direction: column;
    .content_card{
    flex-wrap: wrap;
    width: 921px;
    padding-top: 2rem;

    }
}
 .btn {
        padding: 0.5rem;
        margin-bottom: 2rem;
        width: 140px;
        color: white;
        background-color:$dc_primary_color;
        border: none;
        font-family: 'Open Sans Condensed', sans-serif;
   
    }
.content {
    width: 100%;
    background-color: $dc_primary_color;
    justify-content: center;
    .card{
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