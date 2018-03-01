<template>
  <v-layout column justify-center align-center>
    <v-flex text-xs-center xs12 sm8 md6>
      <v-card>
        <v-card-media src="/myface.jpg" />
        <v-card-title class="headline">About Me</v-card-title>
        <v-card-text>
          <div>
            <p>
              Hi! My name is Ashton Scott Hellwig. I live in Lafayette, Colorado
                with my lovely girlfriend Victoria Sanchez. While we do not
                currently have any dogs of our own, we both have owned many,
                many dogs in the past. I personally have had 1 Siberian Husky, 1
                Alaskan Husky, 1 Yorkipoo, 1 Jack Russel Terrier, Three Poodles,
                and one Austrailian Shepherd.
            </p>
            <p>
              My experience with animals began when I was 12 years old. This was
                the minimum age that was allowed to volunteer the Georgia Small
                Dog Rescue in Atlanta, GA. There I was an adoption specialist.
                In Atlanta I also earned all of my equine experience. I
                volunteered at a barn close by my home outside of the main city.
            </p>
            <p>
              Currently, I am both a dog walker/sitter for WagWalking as well as
                a sourcing agent for Mrs. Green's Remedies. I am also a college
                sophomore at Front Range Community College where I switched my
                major from Chemistry to Mathematics, and now Computational
                Mathematics for a career in veterinary bioinformatics.
            </p>
          </div>
          <hr class="my-3">
          <v-container fill-height="fluid">
            <v-flex text-xs-left>
              <a href="https://github.com/ashellwig/" target="_blank">My GitHub</a>
              <br>
              <a href="https://facebook.com/AshtonATL/" target="_blank">My Facebook</a>
              <br>
              <a href="https://twitter.com/hellwigashton/" target="_blank">My Twitter</a>
              <br>
              <a href="https://linkedin.com/in/ahellwig/" target="_blank">My LinkedIn</a>
              <br>
              <a href="https://instagram.com/thesocialengineer/" target="_blank">My Instagram</a>
              <br>
              <a href="https://instagram.com/gokuthekittycat/" target="_blank">My Cat's Instagram</a>
            </v-flex>
            <v-flex text-xs-right>
              <img src="/myface.jpg" height="175px" />
            </v-flex>
          </v-container>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn flat color="primary" nuxt to="/services">Next</v-btn>
        </v-card-actions>
      </v-card>
      <v-spacer></v-spacer>
      <blockquote class="blockquote">
        &#8220;When an eighty-five pound mammal licks your tears away, then tries to sit in your lap, it's hard to feel sad.&#8221;
        <footer>
          <small>
            <em>&mdash;Kristan Higgins</em>
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>

