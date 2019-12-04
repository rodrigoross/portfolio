<template>
  <div class="home">
    <img alt="Ross logo" src="../assets/ross.png">
    <HelloWorld msg="Site em construção. Será atualizado o mais breve possivel."/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
  },
};
</script>
