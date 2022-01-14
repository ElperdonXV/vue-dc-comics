<template>
  <footer>
      <div class="top">
          <div class="container clearfix">
              <div class="big-col-sx float">
                  <div class="col-1">
                      <h1>Dc Comics</h1>
                      <ul>
                          <li>
                              <a href="">Characters</a>
                          </li>
                          <li>
                              <a href="">Comics</a>
                          </li>
                          <li>
                              <a href="">Movies</a>
                          </li>
                          <li>
                              <a href="">Tv</a>
                          </li>
                          <li>
                              <a href="">Games</a>
                          </li>
                          <li>
                              <a href="">Video</a>
                          </li>
                          <li>
                              <a href="">News</a>
                          </li>
                      </ul>
                      <h1>Shop</h1>
                      <ul>
                          <li>
                              <a href="">Shop DC</a>
                          </li>
                          <li>
                              <a href="">Shop DC Collectibles</a>
                          </li>
                      </ul>  
                  </div>
                  <div class="col-2">
                      <h1>Dc</h1>
                      <ul>
                          <li>
                              <a href="">Therms of use</a>
                          </li>
                          <li>
                              <a href="">Privacy Policy</a>
                          </li>
                          <li>
                              <a href="">Ad choises</a>
                          </li>
                          <li>
                              <a href="">Advertising</a>
                          </li>
                          <li>
                              <a href="">Jobs</a>
                          </li>
                          <li>
                              <a href="">Subscriptions</a>
                          </li>
                          <li>
                              <a href="">Talent Workshops</a>
                          </li>
                      </ul>
                  </div>
                  <div class="col-3">
                      <h1>Sites</h1>
                      <ul>
                          <li>
                              <a href="">DC</a>
                          </li>
                          <li>
                              <a href="">MAD Magazine</a>
                          </li>
                          <li>
                              <a href="">DC kids</a>
                          </li>
                          <li>
                              <a href="">DC universe</a>
                          </li>
                          <li>
                              <a href="">DC Power Visa</a>
                          </li>
                      </ul>
                  </div>
              </div>
              <div class="big-col-dx float">
                  <img src="../assets/img/dc-logo-bg.png" alt="">
              </div>
          </div>
      </div>
      <div class="bottom">
          <div class="container"></div>
      </div>
  </footer>
</template>

<script>
export default {
    name:'Footer',
    data (){

    }
}
</script>

<style lang="scss" scoped>
    ul{
        list-style: none;
    }
    a{
        text-decoration: none;
        color: grey;
    }
    h1{
        color: white;
        margin: 5px 0;
        text-transform: uppercase;
    }
    .top{
        height: 450px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        align-items: center;
        .big-col-sx{
            width: 50%;
            height: 450px;
            display: flex;
            justify-content: space-between;
            flex-wrap: nowrap;
        }
        .big-col-dx{
            width: 50%;
            height: 450px;
            text-align: right;
            position: relative;
            img{
                position: absolute;
                top: -20;
                right: 0;
                height: 450px;
            }
        }
    }
    .bottom{
        background-color: grey;
    }
</style>