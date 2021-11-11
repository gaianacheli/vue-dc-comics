<template>
  <div class="site_header">
    <nav class="navbar">
      <img class="logo" src="../assets/dc-logo.png" alt="">
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a class="comics" href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMIS</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'SiteHeader',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans+Extra+Condensed:wght@400&display=swap');
.navbar{
  padding-top: 1.5rem;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  
 ul {
  list-style-type: none;
  padding: 0;
 li{
  display: inline-block;
  margin: 0 15px;
  a{
    color: black;
    text-decoration: none;
    font-size: 11px;
    font-family: 'Fira Sans Extra Condensed', sans-serif;
    &:hover{
      color: rgba(2, 130, 249, 1);
      border-bottom: 4px solid rgba(2, 130, 249, 1);
      padding-bottom: 2rem;
    }
  }
}
}
}
.logo{
  width: 70px;
  padding-bottom: 1rem;
  
}
</style>
