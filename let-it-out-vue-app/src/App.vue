<template>
  <div>
    <Headerpage />
    <router-view></router-view>
    <Footerpage />
  </div>

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
