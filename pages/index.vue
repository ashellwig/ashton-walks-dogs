<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <img src="/waglogo.png" alt="wagwalking.com" height="50px" />
        <blockquote class="blockquote">
          &#8220;When an eighty-five pound mammal licks your tears away, then tries to sit in your lap, it's hard to feel sad.&#8221;
          <footer>
            <small>
              <em>&mdash;Kristan Higgins</em>
            </small>
          </footer>
        </blockquote>
      </div>
      <v-card>
        <v-card-title class="headline">Ashton Hellwig :: Dog Walker</v-card-title>
        <v-card-text>
          <div>
          <p>
            Hello! Welcome to my website. This site here is dedicated to my
              dog walking business. By clicking continue, you will be brought
              to my "About" page, which is where I will discuss a little bit
              about me before I go into the services that I provide.
          </p>
          </div>
          
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn color="primary" flat nuxt to="/about">Continue</v-btn>
        </v-card-actions>
      </v-card>
      
    </v-flex>
  </v-layout>
</template>


