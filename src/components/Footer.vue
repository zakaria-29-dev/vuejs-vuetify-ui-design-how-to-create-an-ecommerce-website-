<template>
  <v-footer dark padless>
    <v-card flat tile class="black white--text py-12 px-5" width="100%">
      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-0">
            <h3>AAE IdeaPro</h3>
          </v-card-text>
          <v-card-text class="grey--text pt-0">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.<br />
            esse cupiditate nam repellat hic est excepturi.
          </v-card-text>
          <v-toolbar flat color="transparent">
            <h5>Guides</h5>
            <h5 class="ml-4">Terms of Use</h5>
            <h5 class="ml-4">Privacy Policy</h5>
          </v-toolbar>
          <v-card-text class="grey--text"> &#169; 2021 -2022 </v-card-text>
        </v-col>
        <v-col cols="12" sm="2">
          <v-card-text class="white--text pt-0">
            <h3>Get Help</h3>
          </v-card-text>
          <v-card-text class="grey--text"> Order Status </v-card-text>
          <v-card-text class="grey--text mt-n4">
            Shipping and Delivery
          </v-card-text>
          <v-card-text class="grey--text mt-n4"> Payment Options </v-card-text>
          <v-card-text class="grey--text mt-n4"> Contact US </v-card-text>
        </v-col>
        <v-col cols="12" sm="2">
          <v-card-text class="white--text pt-0">
            <h3>About US</h3>
          </v-card-text>
          <v-card-text class="grey--text"> Careers </v-card-text>
          <v-card-text class="grey--text mt-n4"> Sustainability </v-card-text>
          <v-card-text class="grey--text mt-n4"> Service </v-card-text>
          <v-card-text class="grey--text mt-n4">
            CA Supply Chains Act
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card-text class="pt-0">
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-1 white--text"
              icon
            >
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-text>
          <v-card-text class="grey--text mt-14"> Payment Methods: </v-card-text>
          <v-toolbar flat color="transparent">
            <v-spacer></v-spacer>
            <v-icon large>fab fa-cc-visa</v-icon>
            <v-icon class="mx-2" large>fab fa-cc-paypal</v-icon>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>

<style>
</style>