<template>
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
:root {
  /*Custom Properties*/
  --rojoOscuro: #9a232c;
  --rojoClaro: #bd252c;
  --amarillo: #f2901a;
  --negro: #1f1c1f;
  --naranja: #e95824;
  --azul: #0766a3;
  --anchoPantalla: 1200px;
}

/*Scrollbar*/
::-webkit-scrollbar {
  width: 1.1rem;
}

::-webkit-scrollbar-track {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 95%,
    rgba(154, 35, 44, 1) 100%
  );
}

::-webkit-scrollbar-track:hover,
::-webkit-scrollbar-track:active {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 95%,
    rgba(242, 144, 26, 1) 100%
  );
}

::-webkit-scrollbar-thumb {
  background: linear-gradient(transparent, #9a232c);
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover,
::-webkit-scrollbar-thumb:active {
  background: linear-gradient(transparent, #f2901a);
}
</style>
