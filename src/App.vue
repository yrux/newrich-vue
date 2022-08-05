<template>
  <header-component />
  <!-- BANNER -->
    <section class="top-banner first-col">
        <img src="./assets/images/bside-1.png" alt="" class="f-img fm-1">
        <img src="./assets/images/bside-3.png" alt="" class="f-img fm-2">
        <img src="./assets/images/bside-2.png" alt="" class="f-img fm-3">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-7">
                    <div class="content-area">
                        <h4>HELLO WORLD!</h4>
                        <h3>We are #1  Community For</h3>
                        <h2>dreamers</h2>
                        <a  href="#" class="link-btn w-btn o-btn"><span>Explore our Community</span><i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
                <div class="col-md-5">
                    <div class="img-holder">
                        <img src="./assets/images/banner-img.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- END BANNER -->
    <!-- KNOW -->
    <section class="know-sec">
        <div class="container">
            <h2>The 1% know</h2>
            <p>How To Make Things Happen. <br>Educate Yourself. <br>Become One Of Them Today.</p>
            <a href="" class="link-btn b-btn o-btn"><span>Join the 1% now</span><i class="fa-solid fa-arrow-right"></i></a>
            
        </div>
    </section>
    <!-- KNOW -->
    <!-- WHAT IS -->
    <section class="what-sec">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-8">
                    <div class="content-area">
                        <h2>What is <br>newrich.com ?</h2>
                        <p>Newrich.com is an online networking and learning platform that connects people who are passionate about building the life of their dreams.</p>
                        <h4>Connect with instructors who can guide you along your path</h4>
                        <a href="" class="bg-white link-btn b-btn w-btn"><span>Join the 1% now</span><i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="img-holder">
                        <img src="./assets/images/what-img.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- END WHAT IS -->
    <!-- LEARN SEC -->
    <section class="learn-sec">
        <div class="container">
            <h3>Learn from thousands of instructors who are proven experts in various fields of lifestyle enhancement.</h3>
            <div class="b-style">
                <div class="center-img">
                    <img src="./assets/images/left-line.png" alt="" class="f-img fi-1">
                    <img src="./assets/images/right-lines.png" alt="" class="f-img fi-2">
                    <div class="img-holder">
                        <img src="./assets/images/big-logo.png" alt="">
                    </div>
                    <div class="sec-newrich-img">
                        <img src="./assets/images/new.png" alt="">
                        <img src="./assets/images/life.png" alt="" class="mt-0 pt-1">
                    </div>
                </div>
                
                <div class="f-box l-box fb-1">
                    <div class="icon-area">
                        <img src="./assets/images/build-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Build online businesses</h4></div>
                </div>

                <div class="f-box l-box fb-2">
                    <div class="icon-area">
                        <img src="./assets/images/rebuild-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Rebuild your mindset</h4></div>
                </div>

                <div class="f-box l-box fb-3">
                    <div class="icon-area">
                        <img src="./assets/images/discover-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Disover your purpose</h4></div>
                </div>

                <div class="f-box l-box fb-4">
                    <div class="icon-area">
                        <img src="./assets/images/feed-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Feed your soul</h4></div>
                </div>

                <div class="f-box r-box fb-5">
                    <div class="icon-area">
                        <img src="./assets/images/creat-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Create better relationships</h4></div>
                </div>
                <div class="f-box r-box fb-6">
                    <div class="icon-area">
                        <img src="./assets/images/learn-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Learn more about who you are</h4></div>
                </div>
                <div class="f-box r-box fb-7">
                    <div class="icon-area">
                        <img src="./assets/images/get-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Get into shape.</h4></div>
                </div>
                <div class="f-box r-box fb-8">
                    <div class="icon-area">
                        <img src="./assets/images/express-icn.png" alt="">
                    </div>
                    <div class="txt-area"><h4>Express yourself creatively</h4></div>
                </div>
            </div>
        </div>
    </section>
    <!-- END LEARN SEC -->
    <!-- CONNECT -->
    <section class="conn-sec">
        <div class="container">
            <h3>Connect with other like-minded people from around the globe.</h3>
            <p>Join thousands of other people just like who you are on the path to joining <strong>The New Rich.</strong></p>
            <a href="" class="bg-white link-btn b-btn w-btn"><span>Join the 1% now</span><i class="fa-solid fa-arrow-right"></i></a>
        </div>
    </section>
    <!-- END CONNECT -->
    <!-- WORK -->
    <section class="work-sec">
        <div class="container">
            <h2>What work for one does not always work for all.</h2>
            <h4>Live your truth. Live it your way</h4>
        </div>
    </section>
    <!-- END WORK -->
    <footer-component />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
  }
}
</script>
<style src="../public/css/custom.css">
/* @import '../assets/css/startpage.css'; */
</style>