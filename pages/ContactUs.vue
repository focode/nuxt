<template>
  <v-container fluid>
    <v-layout >
      <v-flex xs4>
        <v-text-field
          name="input-1"
          label="Email"
          id="testing"
        ></v-text-field>
      </v-flex>
      
    </v-layout>
    <v-layout>
       <v-flex xs4>
        <v-text-field
          name="input-1-3"
          label="Mobile"
          single-line
        ></v-text-field>
      </v-flex>
    </v-layout>
    <v-layout>
      <v-flex xs4>
        <v-text-field
          name="input-7-3"
          label="Message here"
          multi-line
        ></v-text-field>
      </v-flex>
    </v-layout>
    <v-layout row wrap align-center>
      <v-flex xs4>
            <v-btn color="red" dark large>Send</v-btn>
      </v-flex>
     
    </v-layout>
  </v-container>
</template>