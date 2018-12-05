<template>
  <div class="contact">
    <h1>Contact Page</h1>
    <!-- various btns -> props, classes, etc. -->
    <v-btn class="pink white--text">Click Me Class</v-btn>
    <v-btn dark depressed color="pink">Click Me (depressed prop)</v-btn>
    <v-btn dark flat color="pink">Click Me (flat prop)</v-btn>
    <hr class="my-4">

    <!-- buttons with icons -> icons from material.io/tools/icons -->
    <v-btn depressed color="pink white--text">
      <v-icon left>email</v-icon>
      <span>Email</span>
    </v-btn>
    <!-- use small to make small, left to arrange icon and text on button-->
    <v-btn small depressed color="blue white--text">
      <v-icon small left>line_weight</v-icon>
      <span>Files</span>
    </v-btn>
    <!-- use large to make the button large -->
    <v-btn large depressed color="indigo white--text">
      <span>Large</span>
      <v-icon large right>perm_media</v-icon>
    </v-btn>
    <!-- use fab prop to make circular icon, small to make it small, depressed to remove drop shadow, color to add colour -->
    <v-btn fab small depressed color="purple white--text">
      <v-icon>favorite</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>
