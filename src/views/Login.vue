<template>
  <div class="login">
     <!-- Breadcumb -->
      <section class="breadcumb_area">
         <div class="container">
            <div class="row">
               <div class="col-xs-12 text-center">
                  <div class="breadcumb_section">
                     <div class="page_title">
                        <h3>Log In</h3>
                     </div>
                     <div class="page_pagination">
                        <ul>
                           <li><a href="index.html">Home</a></li>
                           <li><i class="fa fa-angle-right" aria-hidden="true"></i></li>
                           <li>Log In</li>
                        </ul>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </section>
    <!-- End Breadcumb -->
      
    <!-- Login -->
      <section class="login">
         <div class="container">
            <div class="row">
               <div class="col-sm-4 col-sm-offset-4">
                  <div class="login-panel widget">
                     <div class="login-body">
                        <form>
                           <div class="form-group">
                              <label class="control-label">Email <span class="required">*</span></label>
                              <input type="email" placeholder="Email or Username" class="form-control" v-model="email">
                           </div>
                           <div class="form-group">
                              <label class="control-label">Password <span class="required">*</span></label>
                              <input type="password" placeholder="Password" class="form-control" v-model="password">
                           </div>
                           <div class="form-group">
                              <button class="btn btn-block btn-lg btn-primary" value="Submit">Sign In</button>
                           </div>
                        </form>
                     </div>
                     <div class="login-with-sites">
                        <button class="btn-facebook login-icons btn-lg btn-block"> <i class="fa fa-facebook"></i> Login With Facebook</button>
                        <button class="btn-google login-icons btn-lg btn-block"> <i class="fa fa-google"></i> Login With Google</button>
                     </div>
                     <div class="login-footer">
                        <div class="checkbox checkbox-primary pull-left">
                           <input id="checkbox2" type="checkbox" >
                           <label for="checkbox2">
                           Remember me
                           </label>
                        </div>
                        <p class="text-center pull-right"> <a href="forgot-password.html"> Forgot password? </a> </p>
                        <div class="clearfix"></div>
                     </div>
                  </div>
                  <p class="text-center margin-bottom-none">Don't have an account? <a href="signup.html"><strong>Signup</strong></a></p>
               </div>
            </div>
         </div>
      </section>
      <!-- End Login -->
  </div>
</template>

<script>
import axios from "axios";

export default {
  template: "#login-page",
  data: function() {
    return {
      email: "",
      password: "",
      errors: []
    };
  },
  methods: {
    submit: function() {
      var params = {
        email: this.email,
        password: this.password
      };
      axios
        .post("http://localhost:3000/api/sessions", params)
        .then(response => {
          axios.defaults.headers.common["Authorization"] =
            "Bearer " + response.data.jwt;
          localStorage.setItem("jwt", response.data.jwt);
          this.$router.push("/");
        })
        .catch(error => {
          this.errors = ["Invalid email or password."];
          this.email = "";
          this.password = "";
        });
    }
  }
};
</script>