<template>
  <div id="app">
    <div class="mt-0">
      <b-navbar toggleable="sm" type="light" variant="light" sticky >
        <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

        <b-navbar-brand class="ml-0">
          <b-icon-music-player-fill class="h5 mr-0 mb-0 mt-0" style="color: #17a2b8;"></b-icon-music-player-fill>
          Ubuntu</b-navbar-brand>

        <b-collapse id="nav-text-collapse" is-nav>
          <b-navbar-nav >
            <b-nav-text class="ml-5" tabs align="right" >Login</b-nav-text>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <!-- carosel -->
    <div>
      <b-container align-v="center" >
      <b-carousel
        id="carousel-fade"
        style="text-shadow: 0px 0px 2px #000"
        fade
        indicators
        class="mt-4 mb-5"
      >
        <b-carousel-slide
          caption="Get Apple Music and Netflix for the price of one"
          img-src="./assets/img4.jpg"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Get Apple Music for free by inviting your friends"
          img-src="./assets/img2.jpg"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="You never have to worry about monthly billings again"
          img-src="./assets/img8.jpg"
        ></b-carousel-slide>
      </b-carousel>
      </b-container>
    </div>
    <!-- carosel ends -->
    <h1 class="mt-0">Available Plans</h1>
    <b-container align-v="center" class="container">
          <div class="mt-5">
            <b-card-group deck class="mb-3">
              <!-- card 1 -->
              <b-card border-variant="default" header="Freemium" header-bg-variant="secondary"
                header-text-variant="white" align="center" title="$0/month"
                tag="article" style="max-width: auto;" class="mb-5 mt-2"> <br>
                <b-card-text>Get a free Apple Music subscription for 1 year by 
                  getting 3 of your friends to subcribe for basic or premium  </b-card-text>
               <b-list-group flush>
                  <b-list-group-item></b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Apple Music  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Netflix Family  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Amazon Prime  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Spotify Family  
                  </b-list-group-item>
                  <b-list-group-item></b-list-group-item>
                </b-list-group>
                <br>
                <b-button href="#" variant="secondary">Get Referral Code</b-button> <br>
              </b-card>
              <!-- card 2 -->
              <b-card border-variant="info" header="Basic" header-bg-variant="info"
                header-text-variant="white" align="center" title="$4/month"
                tag="article" style="max-width: auto;" class="mb-5 mt-2"> <br>
                <b-card-text>Get a 1 year subscription to both
                   Apple Music & Netflix. This is billed once for the year</b-card-text>
                <b-list-group flush>
                  <b-list-group-item></b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Apple Music  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Netflix Family  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Amazon Prime  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Spotify Family  
                  </b-list-group-item>
                  <b-list-group-item></b-list-group-item>
                </b-list-group> <br>
                <b-button href="#" variant="info">Subscribe</b-button> <br>
              </b-card>
              <!-- card 3 -->
              <b-card border-variant="default" header="Premium" header-bg-variant="secondary"
                header-text-variant="white" align="center" title="$50/month"
                tag="article" style="max-width: auto;" class="mb-5 mt-2"> <br>
                <b-card-text>Get a 1 year subscription to
                   Apple Music, Netflix and Spotify. This is billed once for the year</b-card-text>
                <b-list-group flush>
                  <b-list-group-item></b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Apple Music  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Netflix Family  
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-x-circle class="h5 mr-2 mb-0 mt-0"></b-icon-x-circle>
                      Amazon Prime  <b-badge variant="primary" pill>coming soon</b-badge>
                  </b-list-group-item>
                  <b-list-group-item>
                      <b-icon-check2-circle class="h5 mr-2 mb-0 mt-0" animation="fade"></b-icon-check2-circle>
                      Spotify Family  
                  </b-list-group-item>
                  <b-list-group-item></b-list-group-item>
                </b-list-group>
                <br>
                <b-button href="#" variant="secondary">Subscribe</b-button>
              </b-card>
            </b-card-group>
          </div>
    </b-container>
    <div class="footer">
      <p>Ubuntu App &copy; 2020</p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'app',
  components:{}
}
</script>

<style>
#app {
  text-align: center;
  font-family: YS Text, Arial, sans-serif;
  font-weight: 300;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 0px;
}
img,.w-100{
  max-width: 1424px !important;
  height: 480px !important;
}
@media (min-width: 481px){
  li{
    width: 960px;
  }
}
@media (min-width: 320px) and (max-width: 480px) {
  li{
    width: auto;
  }
}

</style>
