<template>
  <div>
    <v-container fluid class="grey lighten-5 d-flex align-content-lg-space-between flex-column" style="min-height: 100vh" >
      <v-row align-stretch>
        <v-col>
          <v-card
            height="100%"
            class="pa-2"
            outlined
            tile
          >
            <v-icon>mdi-virus</v-icon>
            Virus
          </v-card>
        </v-col>
        <v-col>
          <v-card
            height="100%"
            class="pa-2"
            outlined
            tile
          >
            <v-icon>mdi-newspaper-variant-outline</v-icon>
            Current Card Area
          </v-card>
        </v-col>
        <v-col
        >
          <v-card
            class="pa-2"
            outlined
            tile
            height="100%"
          >
           <v-icon>mdi-newspaper-variant-multiple-outline</v-icon>
            Event Card Deck
          </v-card>
        </v-col>
      </v-row>
      <v-row align-stretch>
        <v-col>
          <v-card
            height="100%"
            class="pa-2"
            outlined
            tile
          >
            <v-icon>mdi-city-variant</v-icon>
            Cities
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>