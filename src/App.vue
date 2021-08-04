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
  font-family: "DIN-Medium" ;
  src: url('/fonts/DIN Alternate Medium.ttf');
  font-weight: normal;
}
@font-face {
  font-family: "DIN-Light" ;
  src: url('/fonts/DIN Alternate Light.ttf');
  font-weight: normal;
}
@font-face {
  font-family: "DIN-Bold" ;
  src: url('/fonts/DIN Alternate Bold.ttf');
  font-weight: normal;
}
@font-face {
  font-family: "DIN" ;
  src: url('/fonts/DIN Medium.ttf');
  font-weight: normal;
}

html{
  font-family: "DIN-Medium", Arial, sans-serif, Helvetica ;
}
#app {

font-size:16px;
}
</style>
