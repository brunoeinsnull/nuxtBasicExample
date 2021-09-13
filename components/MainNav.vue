<template>
  <v-app-bar app elevation="3" outlined class="appBar" light>
    <!-- -->
       
    <v-spacer></v-spacer>
    <v-toolbar-title width="200" class="tite">Basic Example</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-app-bar-item>
      <nuxt-link to="/">Some Link</nuxt-link>
    </v-app-bar-item>
  </v-app-bar>
</template>

<script>
export default {};
</script>

<style scoped>
.appBar {
  background-color: white;
  color: black;
}
.title {
 text-overflow: show;
  overflow: visible;
}
</style>