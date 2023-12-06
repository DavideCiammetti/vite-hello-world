<script>
import AppHero from './AppHero.vue';
export default{
  name:'appComponent',
    data(){
      return{
        'title': 'La mia prima app con Vite!',
      };
    },
    components:{
      AppHero,
    }
};
</script>

<template>
  <h1>{{ title }}</h1>
  <AppHero/>
</template>

<style scoped>
</style>
