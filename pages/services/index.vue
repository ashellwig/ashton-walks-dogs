<template>
  <v-layout align-content-space-around>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-card-media src="/dogwalkstock_chris-s.jpg" height="300px" />
        <v-card-title class="headline">
          <span>
            <v-icon>directions_walk</v-icon>
            Dog Walking
          </span>
        </v-card-title>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn icon @click.native="show = !show">
            <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
          </v-btn>
        </v-card-actions>
        <v-slide-y-transition>
          <v-card-text v-show="show">
            Placeholder for more information about this category.
          </v-card-text>
        </v-slide-y-transition>
      </v-card>
      <br>
      <v-card>
        <v-card-media src="/dogwalkstock_chris-s.jpg" height="300px" />
        <v-card-title class="headline">
          <span>
            <v-icon>directions_walk</v-icon>
            Dog Sitting
          </span>
        </v-card-title>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn icon @click.native="show = !show">
            <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
          </v-btn>
        </v-card-actions>
        <v-slide-y-transition>
          <v-card-text v-show="show">
            Placeholder for more information about this category.
          </v-card-text>
        </v-slide-y-transition>
      </v-card>
      <br>
      <v-card>
        <v-card-media src="/dogwalkstock_chris-s.jpg" height="300px" />
        <v-card-title class="headline">
          <span>
            <v-icon>directions_walk</v-icon>
            Dog Walking
          </span>
        </v-card-title>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn icon @click.native="show = !show">
            <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
          </v-btn>
        </v-card-actions>
        <v-slide-y-transition>
          <v-card-text v-show="show">
            Placeholder for more information about this category.
          </v-card-text>
        </v-slide-y-transition>
      </v-card>
      <br>
    </v-flex>
  </v-layout>
</template>

<script>
  export default {
    data: () => ({
      show: false
    })
  }
</script>