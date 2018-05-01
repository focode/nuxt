<template>
  <v-app light>
    
     <v-toolbar dark color="red">
   
    <v-toolbar-title to="/" >Adore Software</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat to="/AboutUs">About Us</v-btn>
      <v-btn flat to="/OurWork">Our Work</v-btn>
      <v-btn flat to="/OurPlans">Our Plans</v-btn>
      <v-btn flat to="/ChooseUs">Why Choose us</v-btn>
      <v-btn flat to="/ContactUs">Contact Us</v-btn>
    </v-toolbar-items>
  </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
   
    <v-footer>
     
        <v-layout >
        <v-flex xs3 offset-xs1>
          <v-card dark color="red">
          Features
          <br>
          Android Development
          <br>
          Web Development
          <br>
          Branding and Promotion
          <br>
          CRM and ERP Development
          <br>
          Cloud Base App
          </v-card>
        </v-flex>
       
        <v-flex xs3>
           <v-card dark color="red">
          Services
          <br>
          IT Support
          <br>
          SEO Services
          <br>
          Software Consulting
          <br>
          Open Source
          <br>
          Software Developers
          <br>
          Software Development
          <br>
          Cloud Base App
            </v-card>
        </v-flex>
      
      <v-flex xs3>
        <v-card dark color="red">
         Contact Us!
          <br>
          ####, ## ####, #### #### ####, ######-##, #####, #####, 111111, India
          <br>
          General info@adoresoftware.com
          <br>
          Call Us: +91-8411911414
           </v-card>
        </v-flex>
       
        <v-flex>
          <v-card dark color="red">
          Privacy Policy 
          <br>
          Refund Policy 
          <br>
          Sitemap
          </v-card>
        </v-flex>
        </v-layout>
    
    </v-footer>
  </v-app>
</template>
