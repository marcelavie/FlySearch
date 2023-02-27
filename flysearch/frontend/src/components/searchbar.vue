<template>
    <div >
           <div style="" >

           <!-- container for flight and hotel components -->
           <v-row align="end" justify="center" class="pa-4 white search-container" no-gutters>
                  <div class="pa-6 mr-4" style="width:30%;border:1px solid grey;border-radius:35px;height:140px;display:flex;justify-content:center;align-items:center;">
                      <div style="flex:2;">
                          <br>
                          <p class="font-7 mb-n1">Living from</p>
                          <!-- <p class="font-7 mb-n1 weight-600">Dubai</p> -->
                          <v-text-field value="" color="white" background-color="" class="ml-n3 mb-n1 weight-600 font-7"  solo dense flat></v-text-field>
                      </div>
                      <div style="flex:1">
                          <v-avatar size="26" style="border:2px dotted grey">
                              <v-icon size="16">mdi-airplane</v-icon>
                          </v-avatar>
                      </div>
                       <div style="flex:2;">
                           <br>
                          <p class="font-7 mb-n1">Going to</p>
                          <!-- <p class="font-7 mb-n1 weight-600">Dubai</p> -->
                          <v-text-field value="New York" color="white" background-color="white" class="ml-n3 mb-n1 weight-600 font-7"  solo dense flat></v-text-field>
                      </div>
                  </div>
                  <div class="pa-6 mr-4" style="width:40%;border:1px solid grey;border-radius:35px;height:140px;display:flex;justify-content:center;align-items:center">
                      <div style="flex:2;">
                          <br>
                          <p class="font-7 mb-n1">Leave <v-icon color="blue">mdi-airplane-takeoff</v-icon></p>
                          <!-- <p class="font-7 mb-n1 weight-600">Dubai</p> -->
                          <v-text-field value="23 Jan, Sat" color="white" background-color="white" class="ml-n3 mb-n1 weight-600 font-7"  solo dense flat></v-text-field>
                      </div>
                      <div style="flex:1">
                          <v-avatar size="26" style="border:2px dotted grey">
                              <v-icon size="16">mdi-calendar-multiselect</v-icon>
                          </v-avatar>
                      </div>
                       <div style="flex:2;">
                           <br>
                          <p class="font-7 mb-n1">Return <v-icon color="blue">mdi-airplane-landing</v-icon></p>
                          <!-- <p class="font-7 mb-n1 weight-600">Dubai</p> -->
                          <v-text-field value="14 Jan, Thu" color="white" background-color="white" class="ml-n3 mb-n1 weight-600 font-7"  solo dense flat></v-text-field>
                      </div>
                  </div>
                  <v-btn x-large style="height:140px;width:140px;border-radius:50%" color="#3E86F5CC" dark ><v-icon size="35">mdi-magnify</v-icon></v-btn>
                
           </v-row>
       </div>
    </div>
  </template>

<script>
    export default{
        name: 'searchbar.vue'
    }
</script>

<style>
.search-container{
    border-radius:35px;
    height:200px;
    width:90%;
    border-top-left-radius:0px;
}

@media screen and (max-width:500px) {
 .search-container{
    border-radius:35px;
    height:100px;
    width:90%;
    border-top-left-radius:0px;
}   
}
</style>