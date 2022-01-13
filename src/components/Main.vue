<template>
  <main>
      <div class="top">
          <div class="container">
              <h1>-->Content goes here</h1>
          </div>
      </div>
      <div class="bottom">
          <div class="container">
              <ul>
                  <li>
                      <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
                      <span>Digital comics</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-merchandise.png" alt="Digital comics">
                      <span>dc merchandise</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-subscriptions.png" alt="Digital comics">
                      <span>subscription</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-shop-locator.png" alt="Digital comics">
                      <span>comic shop locator</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-dc-power-visa.svg" alt="Digital comics">
                      <span>dc power visa</span>
                  </li>
              </ul>
          </div>
      </div>
  </main>
</template>

<script>
export default {
    name:'Main',
    data (){

    }
}
</script>

<style lang="scss" scoped>
    .top{
        background-color: black;
        height: 120px;
        display: flex;
        align-items: center;
        h1{
            color: white;
        }
    }
    .bottom{
        background-color: #0282F9;
        height: 170px;
        display: flex;
        align-items: center;
        ul{
            list-style: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
            li{
                display: flex;
                align-items: center;
                gap: 8px;
                height: 40px;
            }
            li span{
                color: white;
                text-transform: uppercase;
            }
            li img{
                height: 100%;
            }
        }
    }
</style>