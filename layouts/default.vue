<template>
  <v-app light>
    
     <v-toolbar dark color="red">
   
    <v-toolbar-title to="/" >Adore Software</v-toolbar-title>
    <v-spacer></v-spacer>

    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat to="/AboutUs">About Us</v-btn>
      <v-btn flat to="/OurWork">Our Work</v-btn>

       <v-menu offset-y>
      <v-btn flat slot="activator" dark>Our Plans</v-btn>
      <v-list>
        <v-list-tile v-for="item in items" :key="item.title" @click="">
          <v-list-tile-title>{{ item.title }}</v-list-tile-title>
        </v-list-tile>
      </v-list>
    </v-menu>

      <v-btn flat to="/ChooseUs">Why Choose us</v-btn>
      <v-btn flat to="/ContactUs">Contact Us</v-btn>

     

    </v-toolbar-items>
  </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
   
   <footer>
    <div class="wrapper">
     
    <div class="box">
       Features
      <hr>
      <li>
         Android Development
      </li>
       <li>
          Web Development
      </li>
       <li>
          Branding and Promotion
      </li>
       <li>
          CRM & ERP Development
      </li>
       <li>
          Cloud Base App
      </li>
    </div>
    <div class="box">
     Services
     <hr>
      <ul>
        <li>
          IT Support
        </li>
        <li>
           SEO Services
        </li>
        <li>
          Software Consulting
        </li>
        <li>
           Open Source
        </li>
         <li>
            Software Developers
        </li>
         <li>
            Cloud Base App
        </li>
        
      </ul>
     
    </div>
    <div class="box">
       Contact Us!
       <hr>
      <ul>
        <li>
           #704, A Tower, <br>
           Samarth Carina,<br> Chinchwad , <br>
           Thegaon Road, Pune, 411033, India <br>
           General info@adoresoftware.com
           Call Us: +91-8411911414
        </li>
      </ul>
      </div>
    
    <div class="box">
      Privacy Policy 
      <hr>
      <ul>
        <li>
          Refund Policy 
        </li>
        <li>
      Sitemap
        </li>
      </ul>
      </div>
     
    </div>
   </footer>
  </v-app>
</template>

<style scoped>
.wrapper {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  background-color: rgb(243, 63, 63);
  color: #444;
  justify-items: center;
  
}

.box {
  background-color:rgb(243, 63, 63);
  color: white;
  padding: 20px;
  font-size: 10;
}
</style>

<script>
  export default {
    data: () => ({
      items: [
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me' },
        { title: 'Click Me 2' }
      ]
    })
  }
</script>

