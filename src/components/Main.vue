<template>
  <v-app id="inspire">
    <Sidebar />

    <v-container fluid>
      <v-row>
        <v-col>
          <Toolbar />
        </v-col>
      </v-row>
      <v-row></v-row>
    </v-container>
  </v-app>
</template>

<script>
import Sidebar from "./Sidebar/Sidebar";
import Toolbar from "./Toolbar/Toolbar";

export default {
  name: "Main",
  components: {
    Sidebar,
    Toolbar
  },
  props: {
    source: String
  },
  data: () => ({
    drawer: null
  }),
  created() {}
};
</script>
