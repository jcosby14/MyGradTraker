<template>  
    <v-container> <!-- provides the ability to center and horizontally pad your site's contents. -->
      <v-row class="text-center">   <!--Centers text on screen --> 
        <v-col cols="12">

          <!-- Below is the code used to add UNA image into Home page -->
              <v-img          
                :src="require('../assets/UNALogo.png')"
                class="my-4"
                contain      
                height="200"
              />
            </v-col>

            <v-col class="mb-4">
              <h1 class="display-1 font-weight-bold mb-3">      <!--makes the text below bold -->
                Welcome to the GradTracker 
              </h1>
    
        </v-col>
      </v-row>
    </v-container>  
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>
