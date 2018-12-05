<template>
  <nav>
    <!-- toolbar -->
    <v-toolbar flat app>
      <!-- toolbar title -> uses different text/col utility classes to create styled logo/brand -->
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Vue.</span>
        <span>Vuetify</span>
      </v-toolbar-title>
      <!-- v-space -> takes up all available room -> forces the button to the right -->
      <v-spacer></v-spacer>
      <!-- sign out button with icon, positioned on right of toolbar -->
      <v-btn flat color="grey">
        <span>Sign Out</span>
        <v-icon right>exit_to_app</v-icon>
      </v-btn>
    </v-toolbar>
  </nav>
</template>

<script>
export default {};
</script>
