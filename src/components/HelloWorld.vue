<template>
<v-container>
  <v-layout
    text-xs-center
    wrap
  >
    <v-flex xs12>
      <h3>Home</h3>
      <router-link to="linkUrl">Home</router-link>
    </v-flex>
  </v-layout>
</v-container>
</template>

<script>
export default {
  data() {
    return {
      linkUrl: '/about'
    };
  }
}
</script>

<style>

</style>
