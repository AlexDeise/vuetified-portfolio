<template>
  <div class="container text-center">
    <h1>About Me</h1>
    <h2>
      <v-icon x-large>mdi-account-hard-hat</v-icon>
      Under Construction!
      <v-icon x-large>mdi-account-hard-hat</v-icon>
    </h2>
    <p>
      Around 2014-2015 I became interested in Astrophotography which eventually
      led me into general photography. I enjoy mixing my hobbies so I bring my
      camera along with me when I go snowboarding or riding my bicycle.
    </p>
<!-- 
    <p>
      While working full time at University of Pittsburgh I enrolled in a few
      computer science courses to learn more around 2016.
    </p>
    <p>
      One of the first projects I created was a static HTML page to host some of
      my photographs (I also became interested in astrophotograph and general
      photography).
    </p>
    <p>
      I continued to self teach but found out about a coding bootcamp in
      Pittsburgh known as Tech Elevator.
    </p>
    <p>
      In September of 2021 I enrolled at Tech Elevator for their 14 week Java
      Full Stack Software Bootcamp
    </p>
    <p>
      While at Tech Elevator I built full stack applications using a Java /
      Postgresql / Vue.js
    </p> -->
    <!-- <p>Check out some of my projects below!</p>
    <v-divider></v-divider>
    <h1>Projects</h1>
    <div class="container" align="center" justify="center">
      <v-row>
        <v-col>
          <v-card width="500px" dark>
            <v-card-title>Photography / Development Portfolio</v-card-title>
            <v-img src="../assets/personalPortfolio_thumb.png"></v-img>
            <v-card-subtitle
              >Vue.js - Vuetify - Vuex - Vue Router</v-card-subtitle
            >
            <v-card-text
              >Feels like web-ception explaining this website while on it. Built
              using Vuetify framework for the first time, exploring all of the
              components it has to offer. Run on a free netlify account and updates from a Github Repo
            </v-card-text>
          </v-card>
        </v-col>
        <v-col>
          <v-card width="500px" dark>
            <v-card-title>Stock Exchange Game</v-card-title>
            <v-img src="../assets/stockGameTwo_thumb.png"></v-img>
            <v-card-subtitle
              >Java / Spring Boot / PostgreSQL / Vue.js</v-card-subtitle
            >
            <v-card-text
              >Full stack stock trading game web application. Users can create a
              "game" where you compete against other users to obtain the most
              money by games chosen end date. <br />
              Implemented YahooFinance external API to fill a PostgreSQL db with
              stock data. Unit testing done with JUnit.
            </v-card-text>
          </v-card>
        </v-col>
        <v-col>
          <div>
            <v-card width="500px" dark>
              <v-card-title>React Dashboard</v-card-title>
              <v-card-subtitle
                ><v-icon x-large>mdi-account-hard-hat</v-icon> Work In
                Progress<v-icon x-large
                  >mdi-account-hard-hat</v-icon
                ></v-card-subtitle
              >
              <v-card-text
                >Built using the react framework for the first time, it contains
                several useful widgets (weather, stocks, task list, calendar) <br>
                Aggregates data from multiple third party APIs (YFinance &
                OpenweatherAPI) to render weather, stocks, and other information<br>
                Future plans include integrating more external APIs such as
                Strava to track cycling, as well as a complete back end so that
                users can customize their own dashboard
              </v-card-text>
            </v-card>
          </div>
        </v-col>
      </v-row>
    </div> -->
    <v-divider></v-divider>
    <h1>Skills / Tech Stack</h1>
    <span class="group">
      <v-icon x-large> mdi-language-java </v-icon>
      <v-icon x-large> mdi-database-search </v-icon>
      <v-icon x-large> mdi-language-html5 </v-icon>
      <v-icon x-large> mdi-language-css3 </v-icon>
      <v-icon x-large> mdi-language-javascript </v-icon>
      <v-icon x-large> mdi-vuejs </v-icon>
      <v-icon x-large> mdi-react </v-icon>
      <v-icon x-large> mdi-bootstrap </v-icon>
      <v-icon x-large> mdi-angular </v-icon>
    </span>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.group {
  display: flex;
  flex: 1;
  justify-content: space-around;
  padding-bottom: 2rem;
  padding-top: 2rem;
}
</style>
