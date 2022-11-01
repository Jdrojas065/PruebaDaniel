<template>
 <v-app>
  <v-main>
    <men></men>
    <!-- <cal></cal>
    <car></car>
    <divi></divi>
    <caro></caro> -->
   </v-main>
   <router-view></router-view>
 </v-app>
 
 
</template>

<script>
import  men from './components/MenuUno.vue';
// import  cal from './components/CalendarioAll.vue';
// import  car from './components/CardsAll.vue';
// import  divi from './components/DividersAll.vue';
// import  caro from './components/CarouAll.vue';

export default {
  name: 'App',

  components: {
    men,
    // cal,
    // car,
    // divi,
    // caro
  },

  data: () => ({
    //
  }),
};
</script>
