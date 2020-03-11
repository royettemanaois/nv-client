<template>

    <v-content>
     
    </v-content>

</template>

<script>
export default {
  name: "Main",
  props: {
    source: String
  },
  data: () => ({
    drawer: null,
  }),
  created() {
    this.$vuetify.theme.dark = true;
  }
};
</script>
