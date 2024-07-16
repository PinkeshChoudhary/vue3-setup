<template>
    <v-app>
      <v-main>
        <v-btn color="primary">Hello, Vuetify!</v-btn>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-view></router-view>
  </v-main>

  </v-app>

</template>

<script>
export default {
  name: 'App'
};
</script>
<style>
@import 'vuetify/styles';
</style>

