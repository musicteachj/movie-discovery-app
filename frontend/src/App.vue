<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <v-app-bar-title>
        <router-link to="/" class="text-decoration-none text-white">
          <v-icon class="me-2">mdi-movie</v-icon>
          MovieDiscover
        </router-link>
      </v-app-bar-title>

      <v-spacer />

      <v-btn to="/" variant="text">Home</v-btn>
      <v-btn to="/about" variant="text">About</v-btn>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
// Main app component with Vuetify layout
</script>

<style scoped>
.v-app-bar-title a {
  color: inherit;
  text-decoration: none;
}
</style>
