<template>
    <div class="site_footer">
        <div class="footer">
            <div class="link_footer">
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
                <div class="comics_footer">
                    <h3 class="titoletto">SITES</h3>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kinds</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
               </div> 
                <div class="comics_footer shop">
                    <h3 class="titoletto">SHOP</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
               </div> 
           </div>
           <div class="footer_img">
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
.footer {
    background-image: url('../assets/footer-bg.jpg');
    display: flex;
    justify-content: space-around;
    
}
.link_footer {
    width: 400px;
    display: flex;
    flex-wrap: wrap;
    padding: 1rem;
}
.comics_footer {
    display: flex;
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
}
 .footer_img{
     width: 346px;
    background-image: url(/img/dc-logo-bg.f4404ce9.png);
    background-size: 345px;
    background-position: center;
 }
 

</style>
