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

<style scoped>

</style>