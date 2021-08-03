<script>
import TheKandaidea from './components/TheKandaidea.vue';
import TheOverview from './components/TheOverview.vue';
import OurProjects from './components/OurProjects.vue';
import TheFooter from './components/TheFooter.vue';

export default {
  components: {
    TheKandaidea,
    TheOverview,
    OurProjects,
    TheFooter

  }
}
</script>

<template>
  <TheKandaidea></TheKandaidea>
  <TheOverview></TheOverview>

  <OurProjects></OurProjects>
  <TheFooter></TheFooter>
</template>

<style>
@font-face {
  font-family: "DIN" ;
  src: url('/fonts/DIN Alternate Black.ttf');
  font-weight: normal;
}
html{
  font-family: "DIN", Arial, sans-serif, Helvetica ;
}
#app {

  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
font-size:16px;
}
</style>
