<template>
  <v-card color="grey lighten-4" flat height="200px">
    <v-toolbar extended extension-height="18" dense style="padding-top: 0.7em">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>New Version</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-badge :content="5" color="green" overlap>
          <v-icon>mdi-cart-outline</v-icon>
        </v-badge>
      </v-btn>

      <v-btn icon>
        <v-badge :content="7" color="green" overlap>
          <v-icon>mdi-bell-outline</v-icon>
        </v-badge>
      </v-btn>
    </v-toolbar>
  </v-card>
</template>
