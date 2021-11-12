<template>
<div class="card flex">
      <img :src="image" alt="">
      <h3>{{title}}</h3>
  </div>
    
</template>


<script>
export default {
    props:{
        image: String,
        title: String
    }
}
</script>

<style scoped lang="scss">
@import "../assets/style/variabili.scss";
@import "../assets/style/common.scss";
 .card{
     width: 152px;
     padding: 1rem;
     flex-direction: column;
     align-items: flex-start;
     

     img{
         width: 130px;
         height: 130px;
     }
     h3 {
         font-size: 13px;
         color: white;
         margin-top: 10px;
         font-family: 'Cantarell', sans-serif;
          text-transform: uppercase;
     }

 }


</style>