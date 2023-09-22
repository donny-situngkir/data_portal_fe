<template>
  <v-layout>
    <v-app-bar>
      <v-app-bar-title>Data Portal</v-app-bar-title>
    </v-app-bar>
    <SidebarVue/>
  </v-layout>
</template>

<script>
import SidebarVue from '../Sidebar/Sidebar.vue';

export default {
  components: {
    SidebarVue
  }
}
</script>

<style>

</style>