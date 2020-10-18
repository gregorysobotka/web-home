<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <!-- <div class="d-flex align-center">
       
      </div> -->

      <v-spacer></v-spacer>

      <v-btn
        to="/settings"
        target="_blank"
        text
      >
        <span class="mr-2">Settings</span>
        <v-icon>mdi-cog</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: "App",

  components: {
    
  },

  data: () => ({
    //
  })
};
</script>
