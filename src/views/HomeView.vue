<template>
  <v-container>
    <v-row justify="center">
      <v-col>
        <v-img
          :src="require('@/assets/logotype.jpg')"
          class="my-3"
          contain
          height="200"
        />
        <div class="display-4 text-center">Haz de tu compra algo sencillo!</div>
        <div class="display-2 text-center grey--text">Descárgatela ya!</div>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="3">
        <a
          href="https://apps.apple.com/us/app/famlist-lista-de-la-compra/id1660114766?uo=2"
        >
          <v-img :src="require('@/assets/appstore.png')" />
        </a>
      </v-col>
      <v-col cols="3">
        <a
          href="https://play.google.com/store/apps/details?id=com.logicgear.famlist"
        >
          <v-img :src="require('@/assets/googleplay.png')" />
        </a>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Home",
});
</script>
