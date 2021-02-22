<template>
  <div>
    <v-app-bar
        color="white"

    >
      <v-img class="img"
             max-width="60"
             max-height="60"
             src="./assets/logo_let_it_out.png">
      </v-img>
      <v-toolbar-title>ET IT OUT</v-toolbar-title>

      <v-spacer></v-spacer>
      <v-btn to="/">
        Home
      </v-btn>

      <v-btn to="/about">
        About
      </v-btn>
    </v-app-bar>
  </div>

</template>

<script>
export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
div{
  font-family: "Quattrocento Sans";
}
</style>
