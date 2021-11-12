<template>
    <div class="site_footer">
        <div class="footer_one flex">
            <div class="link_footer flex">
                <div class="comics_footer">
                    <h3 class="titoletto">DC COMICS</h3>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h3 class="titoletto">SHOP</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
               </div> 
                <div class="comics_footer">
                    <h3 class="titoletto">DC</h3>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
               </div> 
                <div class="comics_footer flex">
                    <h3 class="titoletto">SITES</h3>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kinds</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
               </div> 
           </div>
           <div class="footer_img">
           </div>   
        </div>
        <div class="footer_two">
             <div class="follow flex">
               <div class="entra">
                   <button class="btn">SIGN-UP NOW!</button>
               </div>
               <div class="social flex">
                   <h2 class="follow_social">FOLLOW US</h2>
                   <img class="logo_social" src="../assets/footer-facebook.png" alt="">
                   <img class="logo_social" src="../assets/footer-twitter.png" alt="">
                   <img class="logo_social" src="../assets/footer-youtube.png" alt="">
                   <img class="logo_social" src="../assets/footer-pinterest.png" alt="">
                   <img class="logo_social" src="../assets/footer-periscope.png" alt="">
                 
                 
                   
                   
                   

                   
                  
                   
               </div>
           </div>
        </div>
        
       
    </div>
</template>

<script>
export default {
  name: 'SiteFooter',
}
</script>

<style scoped lang="scss">
@import "../assets/style/variabili.scss";
@import "../assets/style/common.scss";
.footer_one {
    background-image: url('../assets/footer-bg.jpg');
    justify-content: space-around;
    
}
.link_footer {
    width: 400px;
    flex-wrap: wrap;
    padding: 1rem;
}
.comics_footer {
    flex-direction: column;
    text-align: left;
    padding: 1rem;
    li{
        list-style: none;
        font-size: 10px;
        color: rgba(149, 149, 149, 1);
    }
}
.titoletto{
    color: rgba(255, 255, 255, 1);
    font-family: 'Open Sans Condensed', sans-serif;
}
 .footer_img{
    width: 346px;
    background-image: url(/img/dc-logo-bg.f4404ce9.png);
    background-size: 345px;
    background-position: center;
 }
 .footer_two{
     background-color: rgba(48, 48, 48, 1);
 }
 .follow {
     justify-content: space-around;
     padding: 2rem;
 }
 .btn{
     background-color: rgba(48, 48, 48, 1);
     border-color:$dc_primary_color ;
     padding: 0.5rem;
     color: white;
     font-family: 'Open Sans Condensed', sans-serif;
 }
 .social{
     width: 500px;
     align-content: center;
 }
 .logo_social {
     padding: 0rem 0.5rem;
 }
 .follow_social {
     color:$dc_primary_color;
     margin: 0rem 1rem;
     font-family: 'Open Sans Condensed', sans-serif;
 }
 

</style>
