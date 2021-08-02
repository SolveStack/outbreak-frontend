<template>
  <v-container
    fluid
    class="grey lighten-5 d-flex flex-column"
    style="min-height: 92vh"
  >
    <v-row align-stretch height="100%">
      <v-col>
        <v-card height="100%" class="pa-2 virus" outlined tile>
          Virus Area
        </v-card>
      </v-col>
      <v-col>
        <v-card height="100%" class="pa-2" outlined tile>
          <v-icon>mdi-newspaper-variant-outline</v-icon>
          Current Card Area
        </v-card>
      </v-col>
      <v-col>
        <v-card class="pa-2 card-deck" outlined tile height="100%">
          Event Card Deck Area
        </v-card>
      </v-col>
    </v-row>
    <v-row align-stretch height="100%">
      <v-col>
        <v-card height="100%" class="pa-2 city" outlined tile>
          Cities Area
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<style>
.virus {
  background-image: url("data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3C!DOCTYPE svg PUBLIC '-//W3C//DTD SVG 1.1//EN' 'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'%3E%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='%23eeeeee' d='M19.82 14C20.13 14.45 20.66 14.75 21.25 14.75C22.22 14.75 23 13.97 23 13S22.22 11.25 21.25 11.25C20.66 11.25 20.13 11.55 19.82 12H19C19 10.43 18.5 9 17.6 7.81L18.94 6.47C19.5 6.57 20.07 6.41 20.5 6C21.17 5.31 21.17 4.2 20.5 3.5C19.81 2.83 18.7 2.83 18 3.5C17.59 3.93 17.43 4.5 17.53 5.06L16.19 6.4C15.27 5.71 14.19 5.25 13 5.08V3.68C13.45 3.37 13.75 2.84 13.75 2.25C13.75 1.28 12.97 .5 12 .5S10.25 1.28 10.25 2.25C10.25 2.84 10.55 3.37 11 3.68V5.08C10.1 5.21 9.26 5.5 8.5 5.94L7.39 4.35C7.58 3.83 7.53 3.23 7.19 2.75C6.63 1.96 5.54 1.76 4.75 2.32C3.96 2.87 3.76 3.96 4.32 4.75C4.66 5.24 5.2 5.5 5.75 5.5L6.93 7.18C6.5 7.61 6.16 8.09 5.87 8.62C5.25 8.38 4.5 8.5 4 9C3.33 9.7 3.33 10.8 4 11.5C4.29 11.77 4.64 11.93 5 12L5 12C5 12.54 5.07 13.06 5.18 13.56L3.87 13.91C3.45 13.56 2.87 13.41 2.29 13.56C1.36 13.81 .808 14.77 1.06 15.71C1.31 16.64 2.28 17.19 3.21 16.94C3.78 16.78 4.21 16.36 4.39 15.84L5.9 15.43C6.35 16.22 6.95 16.92 7.65 17.5L6.55 19.5C6 19.58 5.5 19.89 5.21 20.42C4.75 21.27 5.07 22.33 5.92 22.79C6.77 23.25 7.83 22.93 8.29 22.08C8.57 21.56 8.56 20.96 8.31 20.47L9.38 18.5C10.19 18.82 11.07 19 12 19C12.06 19 12.12 19 12.18 19C12.05 19.26 12 19.56 12 19.88C12.08 20.85 12.92 21.57 13.88 21.5S15.57 20.58 15.5 19.62C15.46 19.12 15.21 18.68 14.85 18.39C15.32 18.18 15.77 17.91 16.19 17.6L18.53 19.94C18.43 20.5 18.59 21.07 19 21.5C19.7 22.17 20.8 22.17 21.5 21.5S22.17 19.7 21.5 19C21.07 18.59 20.5 18.43 19.94 18.53L17.6 16.19C18.09 15.54 18.47 14.8 18.71 14H19.82M10.5 12C9.67 12 9 11.33 9 10.5S9.67 9 10.5 9 12 9.67 12 10.5 11.33 12 10.5 12M14 15C13.45 15 13 14.55 13 14C13 13.45 13.45 13 14 13S15 13.45 15 14C15 14.55 14.55 15 14 15Z' /%3E%3C/svg%3E");
  background-size: contain;
}
.city {
  background-image: url("data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3C!DOCTYPE svg PUBLIC '-//W3C//DTD SVG 1.1//EN' 'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'%3E%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='%23eeeeee' d='M19,9V7A2,2 0 0,0 17,5H16V2H14V5H13A2,2 0 0,0 11,7V9A2,2 0 0,0 9,11V12H5A2,2 0 0,0 3,14V22H6V20H8V22H12V20H14V22H16V20H18V22H21V11A2,2 0 0,0 19,9M8,18H6V16H8V18M14,18H12V16H14V18M14,14H12V12H14V14M13,9V7H17V9H13M18,18H16V16H18V18M18,14H16V12H18V14Z' /%3E%3C/svg%3E");
  background-size: contain;
}
.card-deck {
  background-image: url("data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3C!DOCTYPE svg PUBLIC '-//W3C//DTD SVG 1.1//EN' 'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'%3E%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='%23eeeeee' d='M4 7V19H19V21H4C2 21 2 19 2 19V7H4M21 5V15H8V5H21M21.3 3H7.7C6.76 3 6 3.7 6 4.55V15.45C6 16.31 6.76 17 7.7 17H21.3C22.24 17 23 16.31 23 15.45V4.55C23 3.7 22.24 3 21.3 3M9 6H12V11H9V6M20 14H9V12H20V14M20 8H14V6H20V8M20 11H14V9H20V11Z' /%3E%3C/svg%3E");
  background-size: contain;
}
</style>
