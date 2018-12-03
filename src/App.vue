<template>
  <div>
    <app-header></app-header>
    <app-body></app-body>
    <app-footer class="mt-4"></app-footer>
  </div>  
</template>

<script>  //importing components to locally
import Header from "./components/Header";
import Footer from "./components/Footer.vue";
import Body from "./components/Body.vue";
export default {
  components: {   //locally register for  components
    "app-header": Header,
    "app-footer": Footer,
    "app-body": Body
  },
  data() {
    return {};
  }
};
</script>
