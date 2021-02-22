<template>
  <v-app id="app" v-bind:style="{ backgroundColor: '#FFE3E3'}">
    <Headerpage />
    <v-main>
      <v-container>
      <router-view></router-view>
      </v-container>
    </v-main>

    <Footerpage />
  </v-app>

</template>

<script>
import Headerpage from "@/components/Headerpage";
import Footerpage from "@/components/Footerpage";

export default {
  name: 'App',

  components: {
    Headerpage,
    Footerpage
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
v-main{
  background-color: #FFE3E3;
}
div{
  font-family: "Quattrocento Sans";
}
</style>
