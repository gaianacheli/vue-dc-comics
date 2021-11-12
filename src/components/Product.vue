<template>
<div class="card">
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
 .card{
     width: 120px;
     padding: 1rem;
     display: flex;
     flex-direction: column;
     align-items: flex-start;
     

     img{
         width: 100px;
         height: 100px;
     }
     h3 {
         font-size: 8px;
         color: white;
         margin-top: 10px;
     }

 }


</style>