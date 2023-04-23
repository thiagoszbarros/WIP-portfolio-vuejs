<template>
  <div>
    <HeaderComponent />
    <BobyComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/Header/HeaderComponent.vue';
import BobyComponent from './components/Body/BobyComponent.vue';
import FooterComponent from './components/Footer/FooterComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    BobyComponent,
    FooterComponent,
  },
  data() {
    return {
      nome: 'App, componente root',
    }
  },
}
</script>
