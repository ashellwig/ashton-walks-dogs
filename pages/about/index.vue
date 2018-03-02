<template>
  <v-layout column justify-center align-center>
    <v-flex text-xs-center xs12 sm8 md6>
      <v-card>
        <v-card-media src="/myface.jpg" />
        <v-card-title class="headline">About Me</v-card-title>
        <v-card-text>
          <div>
            <p>
              Hi! My name is Ashton Scott Hellwig. I live in Lafayette, Colorado with my lovely wife Victoria Sanchez. While we do
              not currently have any dogs of our own, we both have owned many, many dogs in the past. I personally have had
              1 Siberian Husky, 1 Alaskan Husky, 1 Yorkipoo, 1 Jack Russel Terrier, 3 Poodles, and 1 Austrailian Shepherd.
            </p>
            <p>
              My experience with animals began when I was 12 years old. This was the minimum age that was allowed to volunteer the Georgia
              Small Dog Rescue in Atlanta, GA. There I was an adoption specialist. In Atlanta I also earned all of my equine
              experience. I volunteered at a barn close by my home outside of the main city.
            </p>
            <p>
              Currently, I am both a dog walker/sitter for WagWalking as well as a sourcing agent for Mrs. Green's Remedies. I am also
              a college sophomore at Front Range Community College where I switched my major from Chemistry to Mathematics,
              and now Computational Mathematics for a career in veterinary bioinformatics.
            </p>
          </div>
          <hr class="my-3">
          <v-layout align-content-space-around>
          <v-container fill-height="fluid">
              <v-flex>
                <v-btn color="primary" dark href="https://github.com/ashellwig/" target="_blank">
                  <v-icon left>fa-github</v-icon>My GitHub
                </v-btn>
                <br>
                <v-btn color="primary" href="https://facebook.com/AshtonATL/" target="_blank">
                  <v-icon left>fa-facebook</v-icon>My Facebook
                </v-btn>
                <br>
                <v-btn color="primary" href="https://twitter.com/hellwigashton/" target="_blank">
                  <v-icon left>fa-twitter</v-icon>My Twitter
                </v-btn>
                <br>
                <v-btn color="primary" href="https://linkedin.com/in/ahellwig/" target="_blank">
                  <v-icon left>fa-linkedin</v-icon>My LinkedIn
                </v-btn>
                <!-- <br>
                <v-btn color="primary" href="https://instagram.com/thesocialengineer/" target="_blank">
                  <v-icon left>fa-instagram</v-icon>My Instagram
                </v-btn> -->
                <br>
                <v-btn color="primary" href="https://instagram.com/gokuthekittycat/" target="_blank">
                  <v-icon left>fa-instagram</v-icon>My Cat's Instagram
                </v-btn>
              </v-flex>
            <v-flex text-xs-right>
              <img src="/myface.jpg" height="175px" />
            </v-flex>
          </v-container>
          </v-layout>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn flat color="primary" nuxt to="/services">Next</v-btn>
        </v-card-actions>
      </v-card>
      <v-spacer></v-spacer>
    </v-flex>
  </v-layout>
</template>