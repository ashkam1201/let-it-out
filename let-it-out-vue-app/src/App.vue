<template>
  <v-app>
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

div{
  font-family: "Quattrocento Sans";
}
</style>
