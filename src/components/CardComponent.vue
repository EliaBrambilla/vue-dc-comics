<template>
    <div class="cards-container">
      <div class="card">
         <div><img :src="data.thumb" alt=""></div>
         <div><p>{{data.series}}</p></div>
         <div><p>{{data.type}}</p></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
      name: 'CardComponent',
  props:{
      data: Object,
  }
  }
  </script>
  
  <style scoped>
      img{
          width: 100px;
      }
  .cards-container{
          display: flex;
          align-items: center;
          flex-wrap: wrap;
          max-width: 1200px;
          margin: 0 auto;
      }
  .card{
      color: white;
      width: calc(100% / 4);
      height: 150px;
      background-color: bisque;
      padding: 15px;
      display: flex;
      flex-direction: column;
  }
  </style>