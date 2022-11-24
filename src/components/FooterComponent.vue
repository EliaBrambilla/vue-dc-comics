<template>
    <section class="container-footer">
      <div class="bg-blue">
          <div class="container-call-to-action">
              <div class="card-call-to-action">
                  <img class="img-action" src="../assets/vue-dc-comics-1/buy-comics-digital-comics.png" alt="Comic Digital">
                  <p>DIGITAL COMICS</p>
              </div>
              <div class="card-call-to-action"> 
                  <img class="img-action" src="../assets/vue-dc-comics-1/buy-comics-merchandise.png" alt="Comic Digital">
                  <p>DIGITAL COMICS</p>
              </div>
              <div class="card-call-to-action"> 
                  <img class="img-action" src="../assets/vue-dc-comics-1/buy-comics-shop-locator.png" alt="Comic Digital">
                  <p>DIGITAL COMICS</p>
              </div>
              <div class="card-call-to-action"> 
                  <img class="img-action" src="../assets/vue-dc-comics-1/buy-comics-subscriptions.png" alt="Comic Digital">
                  <p>DIGITAL COMICS</p>
              </div>
              <div class="card-call-to-action"> 
                  <img class="img-action" src="../assets/vue-dc-comics-1/buy-dc-power-visa.svg" alt="Comic Digital">
                  <p>DIGITAL COMICS</p>
              </div>
          </div>
      </div>
      <div class="container-menu-footer">
          <menu>
           <div>
              <h1>DC COMICS</h1>
              <ul>
                  <li>CHARACTERS</li>
                  <li>COMICS</li>
                  <li>MOVIE</li>
                  <li>TV</li>
                  <li>GAMES</li>
                  <li>VIDEO</li>
                  <li>NEWS</li>
              </ul>
              <h1>SHOP</h1>
              <ul><li>Shop DC</li> <li>Shop DC Collectionables</li></ul>
           </div>   
           <div>
              <h1>DC COMICS</h1>
              <ul>
                  <li>CHARACTERS</li>
                  <li>COMICS</li>
                  <li>MOVIE</li>
                  <li>TV</li>
                  <li>GAMES</li>
                  <li>VIDEO</li>
                  <li>NEWS</li>
                  <li>Shop DC</li> 
                  <li>Shop DC Collectionables</li>
                  <li>VIDEO</li>
                  <li>NEWS</li>
                  <li>Shop DC</li> 
              </ul>
           </div> 
           <div>
              <h1>DC COMICS</h1>
              <ul>
                  <li>CHARACTERS</li>
                  <li>COMICS</li>
                  <li>MOVIE</li>
                  <li>TV</li>
                  <li>GAMES</li>
                  <li>VIDEO</li>
                  <li>NEWS</li>
                  <li>Shop DC</li> 
                  <li>Shop DC Collectionables</li>
                  <li>VIDEO</li>
                  <li>NEWS</li>
                  <li>Shop DC</li> 
              </ul>
           </div>       
          </menu>
      </div>
      <div class="container-singup"></div>
    </section>
  </template>
  
  <script>
  export default {
  name: 'FooterComponent'
  }
  </script>
  
  <style scoped lang="scss">
  $container-standard: 1200px;
  $zero-auto: 0 auto;
  .container-call-to-action{
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: $zero-auto;
      color: white;
      width: $container-standard;
  }
  .card-call-to-action{
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 30px;
      font-size: small;
  }
  .bg-blue{
      background-color: hsl(208.9, 98.4%, 49.2%);
  }
  .img-action{
      width: 50px;
      margin-left: 5px;
  }
  menu{
      display: flex;
      align-items: center;
      width: $container-standard;
      margin: $zero-auto;
      color: white;
      & ul{
          list-style-type: none;
          font-size: small;
      } & h1{
          padding: 15px 0;
      }
  }
  .container-menu-footer{
      background-image: url(../assets/vue-dc-comics-1/buy-comics-digital-comics.png);
      width: 100%;
      
  }
  </style>