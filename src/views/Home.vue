<template>
  <div class="home">
      <!-- Categories Page Search-->
      <section class="categories-page-search">
         <div class="container">
            <div class="row">
               <div class="main-search-box text-center">
                  <form action="#" method="GET">
                     <div class="col-md-4 col-sm-4 search-input">
                        <input placeholder="What are you looking for...?" class="form-control input-lg search-form" type="text">
                     </div>
                     <div class="col-md-3 col-sm-3 search-input">
                        <select class="form-control input-lg search-form">
                           <option selected="selected" value="">All Categories</option>
                           <option value="Vehicles" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> - Vehicles - </option>
                           <option value="Cars"> Cars</option>
                           <option value="Motorcycles"> Motorcycles</option>
                           <option value="Boats"> Boats</option>
                           <option value="Vehicles"> Other Vehicles</option>
                           <option value="House" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> -
                              House and Children - 
                           </option>
                           <option value="Appliances"> Appliances</option>
                           <option value="Inside"> Inside</option>
                           <option value="Games"> Games and Clothing</option>
                           <option value="Garden"> Garden</option>
                           <option value="Multimedia" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> - Multimedia - </option>
                           <option value="Telephony"> Telephony</option>
                           <option value="Image"> Image and sound</option>
                           <option value="Real" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> -
                              Real Estate - 
                           </option>
                           <option value="Apartment"> Apartment</option>
                           <option value="Home"> Home</option>
                           <option value="Vacation"> Vacation Rentals</option>
                           <option value="Grounds"> Grounds</option>
                           <option value="Houseshares"> Houseshares</option>
                           <option value="Other real estate"> Other real estate</option>
                           <option value="Services" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> - Services - </option>
                           <option value="Jobs"> Jobs</option>
                           <option value="Job application"> Job application</option>
                           <option value="Services"> Services</option>
                           <option value="dropoff" style="background-color:#E9E9E9;font-weight:bold;" disabled="disabled"> - Extra - </option>
                           <option value="Other"> Other</option>
                        </select>
                     </div>
                     <div class="col-md-3 col-sm-3 search-input">
                        <select class="form-control input-lg search-form">
                           <option selected="selected" value="">All Locations</option>
                           <option value="AL">Alabama</option>
                           <option value="AK">Alaska</option>
                           <option value="AZ">Arizona</option>
                           <option value="AR">Arkansas</option>
                           <option value="CA">California</option>
                           <option value="CO">Colorado</option>
                           <option value="CT">Connecticut</option>
                           <option value="DE">Delaware</option>
                           <option value="DC">District Of Columbia</option>
                           <option value="FL">Florida</option>
                           <option value="GA">Georgia</option>
                           <option value="HI">Hawaii</option>
                           <option value="ID">Idaho</option>
                           <option value="IL">Illinois</option>
                           <option value="IN">Indiana</option>
                           <option value="IA">Iowa</option>
                           <option value="KS">Kansas</option>
                           <option value="KY">Kentucky</option>
                           <option value="LA">Louisiana</option>
                           <option value="ME">Maine</option>
                           <option value="MD">Maryland</option>
                           <option value="MA">Massachusetts</option>
                           <option value="MI">Michigan</option>
                           <option value="MN">Minnesota</option>
                           <option value="MS">Mississippi</option>
                           <option value="MO">Missouri</option>
                           <option value="MT">Montana</option>
                           <option value="NE">Nebraska</option>
                           <option value="NV">Nevada</option>
                           <option value="NH">New Hampshire</option>
                           <option value="NJ">New Jersey</option>
                           <option value="NM">New Mexico</option>
                           <option value="NY">New York</option>
                           <option value="NC">North Carolina</option>
                           <option value="ND">North Dakota</option>
                           <option value="OH">Ohio</option>
                           <option value="OK">Oklahoma</option>
                           <option value="OR">Oregon</option>
                           <option value="PA">Pennsylvania</option>
                           <option value="RI">Rhode Island</option>
                           <option value="SC">South Carolina</option>
                           <option value="SD">South Dakota</option>
                           <option value="TN">Tennessee</option>
                           <option value="TX">Texas</option>
                           <option value="UT">Utah</option>
                           <option value="VT">Vermont</option>
                           <option value="VA">Virginia</option>
                           <option value="WA">Washington</option>
                           <option value="WV">West Virginia</option>
                           <option value="WI">Wisconsin</option>
                           <option value="WY">Wyoming</option>
                           <option value="Other-Locations">Other Locations</option>
                        </select>
                     </div>
                     <div class="col-md-2 col-sm-2 search-input">
                        <button class="btn btn-primary btn-lg simple-btn btn-block">
                        <i class="fa fa-search"></i> Search
                        </button>
                     </div>
                  </form>
               </div>
            </div>
            <div class="row">
               <!-- Categories Page Nav -->
               <div class="all-categories-nav">
                  <a href="#Restaurant">
                     <i class="fa fa-glass shortcut-icon icon-blue"></i> 
                     <p>Restaurant <small>5,56 Ads</small></p>
                  </a>
                  <a href="#Real_Estate">
                     <i class="fa fa-home shortcut-icon icon-green"></i> 
                     <p>Real Estate <small>9,156 Ads</small></p>
                  </a>
                  <a href="#Cars">
                     <i class="fa fa-car shortcut-icon icon-brown"></i> 
                     <p>Cars <small>6,16 Ads</small></p>
                  </a>
                  <a href="#Shopping">
                     <i class="fa fa-shopping-cart shortcut-icon icon-violet"></i> 
                     <p>Shopping <small>98,156 Ads</small></p>
                  </a>
                  <a href="#Job">
                     <i class="fa fa-briefcase shortcut-icon icon-dark-blue"></i> 
                     <p>Job <small>9,16 Ads</small></p>
                  </a>
                  <a href="#Hotels">
                     <i class="fa fa-building-o shortcut-icon icon-orange"></i> 
                     <p>Hotels <small>6,56 Ads</small></p>
                  </a>
                  <a href="#Services">
                     <i class="fa fa-star shortcut-icon icon-light-blue"></i> 
                     <p>Services <small>2,156 Ads</small></p>
                  </a>
                  <a href="#Pets">
                     <i class="fa fa-paw shortcut-icon icon-light-green"></i> 
                     <p>Pets <small>9,156 Ads</small></p>
                  </a>
               </div>
               <!-- End Categories Page Nav -->
            </div>
         </div>
      </section>
      <!-- End Categories Page Search-->
      
    <!-- Categories List Page -->
      <section class="categories-list main-categories-list">
         <div class="container">
            <div v-for="category in categoryReceipts" id="Restaurant" class="row">
               <div class="col-lg-3 col-md-3 col-sm-3">
                  <div class="widget blue-widget">
                     <div class="widget-header">
                        <small>98,156 Ads</small>
                        <h1><i class="fa fa-glass shortcut-icon icon-blue"></i>{{ category.name }}</h1>
                        <h1>You have {{ category.receipts.length }} total receip</h1>
                     </div>
                     <div class="widget-body">
                        <ul class="trends">
                           <li><a href="#"><span class="item-numbers"> </span></a></li>
                        </ul>
                     </div>
                  </div>
               </div>
               <div class="col-lg-9 col-md-9 col-sm-9">
                  <div class="single-categorie">
                     <div id="owl-carousel-featured" style="display: flex" class="owl-carousel categories-list-page owl-theme">
                        <div v-for="receipt in category.receipts" class="item">
                           <div class="item-ads-grid icon-blue">
                              <div class="item-img-grid">
                                 <img alt="" v-bind:src="receipt.image" class="img-responsive img-center">
                                 <div class="item-title">
                                    <a href="single.html">
                                       <h4>{{ receipt.merchant }}</h4>
                                    </a>
                                    <h3> ${{ receipt.price }}</h3>
                                 </div>
                              </div>
                              <div class="item-meta">
                                 <ul>
                                    <li class="item-date"><i class="fa fa-clock-o"></i> Today 10.35 AM</li>
                                    <li class="item-cat"><i class="fa fa-glass"></i> <a href="#">Restaurant</a> , <a href="#">Cafe</a></li>
                                    <li class="item-location"><a href="#"><i class="fa fa-map-marker"></i> Buffalo </a></li>
                                    <li class="item-type"><i class="fa fa-bookmark"></i> New</li>
                                 </ul>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div> 
               </div>
            </div>
         </div>
      </section>
      <!-- End Categories List Page -->
      
    
      
  </div>
</template>

<style>
</style>


<script>
var axios = require("axios");


export default {
  data: function() {
    return {
      receipts: [],
      categories: [],
      categoriesWithReceipts: [],
      searchFilter: "",
      categoryUser: [],
      newSpendingCap: ""
    };
  },
  created: function() {
    axios.get("http://localhost:3000/api/categories/").then(
      function(response) {
        this.categories = response.data.name;
        console.log(this.categories);
      }.bind(this)
    );
    axios.get("http://localhost:3000/api/receipts/").then(
      function(response) {
        console.log(response.data);
        this.receipts = response.data;
        // this.categoryReceipts()
        console.log(this.categories, "code")
      }.bind(this)
    );
  },
  computed: {
    categoryReceipts: function() {
      const categories = this.categories;
      const receipts = this.receipts;
      for(var i = 0; i < categories.length; i += 1) {
          categories[i].receipts = [];
        for(var j = 0; j < receipts.length; j += 1) {
          if (categories[i].id === receipts[j].id) {
            categories[i].receipts.push(receipts[j])
          }
        }
      }
      console.log(categories);
      return categories;
    }
    
  },
  watch: {
    categories: {
      handler: function(newValue) {
        console.log(newValue, "newValue");
        this.categoriesWithReceipts = newValue;
      },
      deep: true
    }
  }, 
  // computed: {}
};
</script>
