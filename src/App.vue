<template>
  <div id="app">
      <!-- Preloder -->
      <div id="preloader"></div>
      <!-- End Preloder -->
      <!-- Navbar -->
      <nav class="navbar top-navbar" role="navigation">
         <div class="container">
            <div class="navbar-header col-sm-2">
               <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
               <span class="sr-only">Toggle navigation</span>
               <span class="icon-bar"></span>
               <span class="icon-bar"></span>
               <span class="icon-bar"></span>
               </button>
               <a class="navbar-brand" href="index.html"><img alt="logo" src="https://img-premium.flaticon.com/png/512/3734/3734708.png?token=exp=1621286850~hmac=b64b596f92f407b995d7dbde0c469b98" ></a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
               <ul class="nav navbar-nav">
                  <li><a href="index.html">Home</a></li>
                  <li class="dropdown">
                     <a data-toggle="dropdown" class="dropdown-toggle" href="#" aria-expanded="false"> Categories Pages <b class="caret"></b></a>
                     <ul class="dropdown-menu">
                        <li>
                           <a href="categories.html"><i class="fa fa-fw fa-angle-right"></i> Categories</a>
                        </li>
                        <li>
                           <a href="category-grid.html"><i class="fa fa-fw fa-angle-right"></i> Category Grid</a>
                        </li>
                        <li>
                           <a href="single.html"><i class="fa fa-fw fa-angle-right"></i> Single Item</a>
                        </li>
                     </ul>
                  </li>
                  <li><a href="pricing.html">Pricing</a></li>
                  <li><a href="faq.html">FAQ</a></li>
                  <li><a href="contact.html">Contact Us</a></li>
                  <li class="dropdown">
                     <a data-toggle="dropdown" class="dropdown-toggle" href="#" aria-expanded="false">Blog <b class="caret"></b></a>
                     <ul class="dropdown-menu">
                        <li>
                           <a href="blog.html"><i class="fa fa-fw fa-angle-right"></i> Blog</a>
                        </li>
                        <li>
                           <a href="blog_details.html"><i class="fa fa-fw fa-angle-right"></i> Blog Details</a>
                        </li>
                     </ul>
                  </li>
                  <li class="dropdown">
                     <a data-toggle="dropdown" class="dropdown-toggle" href="#" aria-expanded="false"> Other Pages <b class="caret"></b></a>
                     <ul class="dropdown-menu">
                        <li>
                           <a href="create_post.html"><i class="fa fa-fw fa-angle-right"></i> Post Your Ad</a>
                        </li>
                        <li>
                           <a href="settings.html"><i class="fa fa-fw fa-angle-right"></i> Settings</a>
                        </li>
                        <li>
                           <a href="close-account.html"><i class="fa fa-fw fa-angle-right"></i> Close account</a>
                        </li>
                        <li>
                           <a href="my-ads.html"><i class="fa fa-fw fa-angle-right"></i> My Ads</a>
                        </li>
                        <li>
                           <a href="favourite.html"><i class="fa fa-fw fa-angle-right"></i> Favourite Ads</a>
                        </li>
                        <li>
                           <a href="privacy.html"><i class="fa fa-fw fa-angle-right"></i> Privacy Policy</a>
                        </li>
                        <li>
                           <a href="404.html"><i class="fa fa-fw fa-angle-right"></i> 404</a>
                        </li>
                     </ul>
                  </li>
               </ul>
               <div class="user-login pull-right">
                  <a href="/#/Signup">REGISTER</a>
                  <span>or</span>  
                  <a class="btn btn-md btn-primary" href="/#/Login">Sign In</a>
               </div>
            </div>
         </div>
      </nav>
      <!-- End Navbar -->
      <router-view />
      <!-- Footer -->
      <footer>
         <section class="footer-Content">
            <div class="container">
               <div class="row">
                  <div class="col-md-3 col-sm-6 col-xs-12">
                     <div class="footer-widget">
                        <h3 class="block-title">About</h3>
                        <div class="textwidget">
                           <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque lobortis tincidunt est, et euismod purus suscipit quis. Etiam euismod ornare elementum. Sed ex est,  Sed ex est, consectetur eget consectetur, Lorem ipsum dolor sit amet...</p>
                        </div>
                     </div>
                  </div>
                  <div class="col-md-3 col-sm-6 col-xs-12">
                     <div class="footer-widget">
                        <h3 class="block-title">Categories</h3>
                        <ul class="menu">
                           <li><a href="#"><span>562</span> Restaurant</a></li>
                           <li><a href="#"><span>451</span> Real Estate</a></li>
                           <li><a href="#"><span>352</span> Cars</a></li>
                           <li><a href="#"><span>312</span> Shopping</a></li>
                           <li><a href="#"><span>262</span> Job</a></li>
                           <li><a href="#"><span>152</span> Hotels</a></li>
                           <li><a href="#"><span>102</span> Services</a></li>
                           <li><a href="#"><span>100</span> Pets</a></li>
                           <li><a href="#"><span>95</span> Cars</a></li>
                           <li><a href="#"><span>85</span> Shopping</a></li>
                           <li><a href="#"><span>50</span> Job</a></li>
                           <li><a href="#"><span>25</span> Hotels</a></li>
                        </ul>
                     </div>
                  </div>
                  <div class="col-md-3 col-sm-6 col-xs-12">
                     <div class="footer-widget">
                        <h3 class="block-title">Latest Post</h3>
                        <ul class="blog-footer">
                           <li>
                              <a href="#">Lorem ipsum dolor sit amet, quem...</a>
                              <span class="post-date"><i class="fa fa-calendar" aria-hidden="true"></i> March 12, 2017</span>
                           </li>
                           <li>
                              <a href="#">Full Width Media Post Lorem ipsum..</a>
                              <span class="post-date"><i class="fa fa-calendar" aria-hidden="true"></i> September 25, 2017</span>
                           </li>
                           <li>
                              <a href="#">Perfect Video Post Lorem ipsum..</a>
                              <span class="post-date"><i class="fa fa-calendar" aria-hidden="true"></i> November 19, 2017</span>
                           </li>
                        </ul>
                     </div>
                  </div>
                  <div class="col-md-3 col-sm-6 col-xs-12">
                     <div class="footer-widget">
                        <h3 class="block-title">Quick Links</h3>
                        <ul class="menu">
                           <li><a href="#">Home</a></li>
                           <li><a href="#">About</a></li>
                           <li><a href="#">FAQ</a></li>
                           <li><a href="#">Careers</a></li>
                           <li><a href="#">Pricing Plans</a></li>
                           <li><a href="#">Categories</a></li>
                           <li><a href="#">Services</a></li>
                           <li><a href="#">Team</a></li>
                           <li><a href="#">Contact</a></li>
                           <li><a href="#">Blog</a></li>
                           <li><a href="#">Help</a></li>
                           <li><a href="#">Advertise With Us</a></li>
                        </ul>
                     </div>
                  </div>
               </div>
            </div>
         </section>
         <div class="copyright">
            <div class="container">
               <div class="row">
                  <div class="col-md-12">
                     <div class="bottom-social-icons social-icon text-center">  
                        <a href="#" target="_blank" class="facebook"><i class="fa fa-facebook"></i></a> 
                        <a href="#" target="_blank" class="twitter"><i class="fa fa-twitter"></i></a>
                        <a href="#" target="_blank" class="dribble"><i class="fa fa-dribbble"></i></a>
                        <a href="#" target="_blank" class="youtube"><i class="fa fa-youtube"></i></a>
                        <a href="#" target="_blank" class="google-plus"><i class="fa fa-google-plus"></i></a>
                        <a href="#" target="_blank" class="linkedin"><i class="fa fa-linkedin"></i></a>
                     </div>
                     <div class="site-info text-center">
                        <p>&copy; Copyright 2017 Osahan - Ads . All Rights Reserved<br> Made with <i class="fa fa-heart"></i> by <a target="_blank" href="https://www.facebook.com/iamgurdeeposahan"><strong>Osahan Studio</strong></a></p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </footer>
      <!-- End Footer -->
  </div>
</template>

<style>
</style>
