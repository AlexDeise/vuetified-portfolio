<template>
  <v-main class="pt-2 pt-sm-2 pt-xs-2 pt-md-0 pt-lg-0 pt-xl-0">
    <v-container>
      <div class="container" align="center" justify="center">
        <h1></h1>
        <h2>Software Developer</h2>
        <h3>Hobbyist Photographer</h3>
        <v-divider></v-divider>
        <div class="container">
          <v-row align="center" justify="center">
            <v-col>
              <v-card width="500px" dark link :to="items[2].to">
                <v-img src="../assets/andromeda_thumb.jpg"> </v-img>
                <v-card-title class="justify-center"
                  >Astrophotography</v-card-title
                >
              </v-card>
            </v-col>
            <v-col>
              <v-card width="500px" dark link :to="items[3].to">
                <v-img src="../assets/frontboard_thumb.jpg"> </v-img>
                <v-card-title class="justify-center">Sports</v-card-title>
              </v-card>
            </v-col>
            <v-col>
              <v-card width="500px" dark link :to="items[4].to">
                <v-img src="../assets/treemilkyway_thumb.jpg"> </v-img>
                <v-card-title class="justify-center"
                  >Landscape / Cityscape</v-card-title
                >
              </v-card>
            </v-col>
            <v-col>
              <v-card width="500px" dark link :to="items[5].to">
                <v-img src="../assets/antwaanCrystalMtn_thumb.jpg"> </v-img>
                <v-card-title class="justify-center">Portraits</v-card-title>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </div>
    </v-container>
  </v-main>
</template>

<script>
export default {
  components: {},
  data: () => ({
    drawer: false,
    items: [
      { title: "Home", icon: "mdi-home-variant-outline", to: "/" },
      { title: "About", icon: "mdi-image", to: "/about" },
      { title: "Astrophotography", icon: "mdi-camera-outline", to: "/astrophotography" },
      { title: "Sports", icon: "mdi-camera-outline", to: "/sports" },
      { title: "CityLandscapes", icon: "mdi-camera-outline", to: "/citylandscapes" },
      { title: "Portraits", icon: "mdi-camera-outline", to: "/portraits" }
      // { title: 'Contact', icon: 'mdi-cellphone-information', to: '/about' }, //Will go live later
    ],
  }),
};
</script>

<style></style>