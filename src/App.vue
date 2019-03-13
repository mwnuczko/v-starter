<template>
<v-app>
  <v-toolbar app>
    <v-toolbar-title class="headline text-uppercase">
      <span>v-starter</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn href="/">
      <span class="mr-2">Home</span>
      <v-icon>home</v-icon>
    </v-btn>
    <v-btn href="/about">
      <span class="mr-2">About</span>
      <v-icon>info</v-icon>
    </v-btn>
  </v-toolbar>

  <v-content>
    <router-view/>
  </v-content>
</v-app>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {};
  }
}
</script>
