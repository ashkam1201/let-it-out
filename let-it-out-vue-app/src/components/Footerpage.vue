<template>
    <v-footer
        class="footer"
        dark
        padless
    >
      <v-card
          color="white"
          class="flex"
          flat
          tile
      >
          <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-4"
              dark
              icon
          >
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        <v-card-text class="py-2 white--text text-center">
          {{ new Date().getFullYear() }} — <strong>Adrian Hagjija</strong>
        </v-card-text>
      </v-card>
    </v-footer>
</template>


<script>
export default {
  name:'Footerpage',
  data: () => ({
    icons: [
      'mdi-facebook',
      'mdi-twitter',
      'mdi-linkedin',
      'mdi-instagram',
    ],
  }),
}
</script>

<style scoped>
v-card-text{
  color: black;
}
i.v-icon.v-icon {
  color: black;
}
.footer{
  bottom:0;
}
</style>
