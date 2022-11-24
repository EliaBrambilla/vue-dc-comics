<template>
  <div class="container">
    <div>
        <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
    </div>
    <nav>
        <ul>
            <li> <a href="#"> CARACTERS </a> </li>
            <li> <a href="#"> COMICS </a> </li>
            <li> <a href="#"> MOVIES </a> </li>
            <li> <a href="#"> TV </a> </li>
            <li> <a href="#"> GAMES </a> </li>
            <li> <a href="#"> COLLECTIBLES </a> </li>
            <li> <a href="#"> VIDEOS </a> </li>
            <li> <a href="#"> FANS </a> </li>
            <li> <a href="#"> NEWS </a> </li>
            <li> <a href="#"> SHOP </a> </li>
        </ul>
    </nav>
    
  </div>
</template>

<script>
export default {
name: 'HeaderComponent'
}
</script>

<style scoped lang="scss">
$zero-auto: 0 auto;
.container{
    margin: $zero-auto;
    margin-top: 30px;
    max-width: 1200px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
ul{
    display: flex;
    justify-content: space-around;
    align-items: center;
    list-style: none;
    & li{
        padding: 10px;
      }
    & a{
        text-decoration: none;
        font-size: small;
        color: black;
        font-weight: bold;
    }
}
</style>