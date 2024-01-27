<script>

export default {
  name:'Exercise',
  data (){
    return{
    title:'Foto del mare',
    color:'red',
    image: 'https://www.focus.it/images/2021/11/23/mare_1020x680.jpg',
    }
    
  }

}
</script>

<template>
  <h1 :class="color">{{ title }}</h1>
  <img :src="image" alt="mare">
</template>

<style >

</style>
