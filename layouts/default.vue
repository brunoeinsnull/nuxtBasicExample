<template>
 <v-app>
  <main-nav></main-nav>

  <!-- Sizes your content based upon application components -->
  <v-main class="main">

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
</template>

<script>
import MainNav from "../components/MainNav.vue";
export default {
  data () {
    return {
     
    }
  },
  components: {
    MainNav
  }
}
</script>
<style scoped>
.main{
  background-color: white;
}
</style>
