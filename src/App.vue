<template>
  <v-app id="inspire">
    <v-navigation-drawer
      dark
      src="./assets/tallmwpanosevensprings_thumb.jpg"
      width="35%"
      app
      temporary
      v-model="drawer"
    >
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="text-h6"> Menu </v-list-item-title>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list dense nav>
        <v-list-item v-for="item in items" :key="item.title" link :to="item.to">
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-app-bar
      app
      shrink-on-scroll
      max-height="1000px"
      src="./assets/westendoverlookcover.jpg"
    >
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      <v-spacer></v-spacer>
      <v-toolbar-title>Alex Deise</v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main dark>
      <router-view></router-view>

      <!-- <hello-world></hello-world> -->
    </v-main>

    <v-footer padless>
      <v-col class="text-center" cols="12">
        {{ new Date().getFullYear() }} — Alex Deise
        <a
          class="instaLink"
          href="https://www.instagram.com/alexdeise/"
          target="_blank"
          ><v-icon>mdi-instagram</v-icon></a
        >
        <p>Get in touch vial Email or Instagram</p>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
export default {
  components: {},
  data: () => ({
    drawer: false,
    items: [
      { title: "Home", icon: "mdi-home-variant-outline", to: "/" },
      { title: "About", icon: "mdi-information-outline", to: "/about" },
      { title: "Astrophotography", icon: "mdi-camera-outline", to: "/astrophotography" },
      { title: "Sports", icon: "mdi-camera-outline", to: "/sports" },
      { title: "CityLandscapes", icon: "mdi-camera-outline", to: "/citylandscapes" },
      { title: "Portraits", icon: "mdi-camera-outline", to: "/portraits" },
      // { title: 'Contact', icon: 'mdi-cellphone-information', to: '/about' }, //Will go live later
    ],
  }),
};
</script>
<style scoped>
.instaLink {
  text-decoration-line: none;
}
</style>
