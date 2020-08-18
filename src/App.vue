<template>
  <v-app>
    <v-app-bar
      app
      color="dark"
      dark
    >

    <v-toolbar-title class="headline text-uppercase">
      <span>Entrainement</span>
      <v-spacer></v-spacer>

      <span class="font-weight-light">Vue.js avec Vuetify et Vue router</span>
    </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn text>
          <router-link to="/">Accueil</router-link>
        </v-btn>
        <v-btn text>
          <router-link to="/about">À propos</router-link>
        </v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
