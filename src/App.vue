<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
   

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <body>

    <!--<img alt="Vue logo" class="logo" src="./assets/c8c8077a-10fc-44d5-93f0-da4e592a299e-netflix-logo-print_pms.jpg" width="400" height="200" />-->
    <TheWelcome />
    </body>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}



@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

 

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

template{
  background-color: black;
}


</style>
