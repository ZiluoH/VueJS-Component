<template>
  <div id="app">
    <div class="container">
      <app-header></app-header>
        <hr>
        <div class="row">
            <app-servers></app-servers>
            <app-server-details></app-server-details>
        </div>
        <hr>
    </div>

    
    <app-footer></app-footer>
    <fruit></fruit>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Fruit from './test.vue'
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Servers from './components/Servers.vue';
import ServerDetails from './components/ServerDetails.vue';

export default {
  components:{
    'fruit': Fruit,
    'app-header': Header,
    'app-servers': Servers,
    'app-server-details': ServerDetails,
    'app-footer': Footer

  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

</style>
