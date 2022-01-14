<template>
  <footer>
      <div class="top">
          <div class="container relative">
              <div class="big-col-sx">
                  <div class="footer-menu">
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
            </div>
              <div class="logo">
                  <img src="../assets/img/dc-logo-bg.png" alt="">
              </div>
          </div>
      </div>
      <div class="bottom">
          <div class="container">
              <div class="footer-end">
                  <a href="" id="button">Signup Now</a>
                  <div class="social">
                      <h3>Follow Us</h3>
                      <div class="icons">
                          <a href="">
                              <img src="../assets/img/footer-facebook.png" alt="">
                          </a>
                          <a href="">
                              <img src="../assets/img/footer-periscope.png" alt="">
                          </a>
                          <a href="">
                              <img src="../assets/img/footer-pinterest.png" alt="">
                          </a>
                          <a href="">
                              <img src="../assets/img/footer-twitter.png" alt="">
                          </a>
                          <a href="">
                              <img src="../assets/img/footer-youtube.png" alt="">
                          </a>
                      </div>
                  </div>
              </div>
          </div>
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
        height: 400px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        align-items: center;
        overflow: hidden;
        .big-col-sx{
            width: 50%;
            padding: 0 20px;
            .footer-menu{
                display: flex;
                justify-content: space-between;
                flex-wrap: nowrap;
                gap: 40px;
            }
        }
        .logo{
            top: -25px;
            right: 0;
            position: absolute;
            img{
                position: absolute;
                top: -30px;
                right: -20px;
                height: 450px;
            }
        }
    }
    .bottom{
        background-color: #303030;
    }
    .footer-end{
        display: flex;
        justify-content: space-between;
        align-items: center;
        #button{
            font-size: 1.3em;
            color: white;
            padding: 10px;
            border: 3px solid #0282F9;
        }
        .social{
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 10px;
            h3{
                color: #0282F9;
                text-transform: uppercase;
            }
            .icons{
                display: flex;
                justify-content: space-between;
                gap: 10px;
            }
        }
    }
</style>