<script>
export default{
  name:'appComponentHero',
    data(){
      return{
        'title': 'app hero con vite',
        'text': 'nuova app con vue',
      };
    },
};
</script>

<template>
  <h3>{{ title }}</h3>
  <p>{{ text }}</p>
</template>

<style scoped>
</style>
