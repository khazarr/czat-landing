<template>
  <v-app dark>

    <v-toolbar color="elevation-0" fixed app>
      <v-toolbar-title v-text="title"></v-toolbar-title>
        <v-spacer />  
        <v-btn flat color="primary">SIGN UP</v-btn>
        <v-btn flat color="primary">PRICING</v-btn>
        <v-btn flat color="primary">ABOUT</v-btn>
        <v-btn flat color="primary">LOGIN</v-btn>
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer :fixed="fixed" app>
      <span>&copy; 2018</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      title: 'Cool chat'
    }
  }
}
</script>
