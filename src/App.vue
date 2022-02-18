<template>
  <v-app id="app">
    <v-btn color="success">Success</v-btn>
    <v-btn color="error">Error</v-btn>
    <v-btn color="warning">Warning</v-btn>
    <v-btn color="info">Info</v-btn>
    <Header />
  </v-app>
</template>

<script>
import Header from './components/Header.vue'

export default {
  components:{Header},
  data() {
    return{
      
    }
  }
}
</script>
