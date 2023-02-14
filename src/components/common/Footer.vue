<template>
   
  <v-container>
    <v-toolbar flat class="mainHeader">
    <v-spacer></v-spacer>
    <v-footer padless>
      <v-card flat class="text-center">
        <v-card-text>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4" icon>
            <v-icon size="24px">{{ icon }}</v-icon>
          </v-btn>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-text>
          {{ new Date().getFullYear() }} —
          <strong>Photography Vuetify 2.1.0 Project</strong>
        </v-card-text>
      </v-card>
    </v-footer>
    <v-spacer></v-spacer>
  </v-toolbar>
  </v-container>

</template>

<script>
export default {
  name: "Header",
  data: () => ({
    icons: [
      "fab fa-facebook",
      "fab fa-twitter",
      "fab fa-google-plus",
      "fab fa-linkedin",
      "fab fa-instagram"
    ]
  })
};
</script>