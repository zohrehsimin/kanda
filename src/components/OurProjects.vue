<script>
import OurProjectsSamples from "./OurProjectsSamples.vue";

export default {
  components: {
    OurProjectsSamples,
  },
  data() {
    return {
      offsetLeftFirstSate: null,
      contents: [
        { src: "/img/1.png", text: "MARINE PLUS SHIP-TRACKING SYSTEM" },
        { src: "/img/2.png", text: "MAP PLUS WEB GIS SOFTWARE" },
        { src: "/img/3.png", text: "GIS-BASED SOFTWARE" },
        { src: "/img/4.jpeg", text: "WATER INFORMATION SYSTEM HEENCO" },
        { src: "/img/5.jpeg", text: "ITEMS SOFTWARE" },
        { src: "/img/6.jpeg", text: "GACHSARAN PETOCHEMICAL PLANT" },
        { src: "/img/7.jpeg", text: "PSEEZ ECONOMICAL AREA IOMS" },
        { src: "/img/8.jpeg", text: "PSEEZ FLARE POSITIONING" },
      ]
    };
  },
  methods: {
    isShownInViewPort(element) {
      const elementRectangle = element.getBoundingClientRect();
      if (
        elementRectangle.top < window.innerHeight &&
        elementRectangle.top + elementRectangle.height > 0
      ) {
        // console.log(elementRectangle.left)

        element.style.left =
          (window.innerWidth * (window.innerHeight - elementRectangle.top)) /
            (window.innerHeight + elementRectangle.height) +
          "px";
      }
    },
  },
  mounted() {
    this.offsetLeftFirstSate = this.$refs.text.getBoundingClientRect().left;
    window.addEventListener(
      "scroll",
      this.isShownInViewPort.bind(this, this.$refs.text)
    );
  },
};
</script>

<template>
  <div class="our-projects-container">
    <div class="our-projects-container__text" ref="text">
      <div class="our-projects-container__text--first-section" >We</div>
      <div>create</div>
    </div>
  <div class="our-projects-sub-container">
    <div class="our-projects-headlines">
      <p class="our-projects-title">OUR PROJECTS</p>
      <p class="our-projects-par">
        Discover the next inspiring talks in industry.
      </p>
    </div>
    <div class="our-projects-samples">
      <div class="our-projects-samples__arrowdown">
        <svg class="arrowdown-icon"  xmlns="http://www.w3.org/2000/svg" width="20px" height="211px">
          <line x1="10" y1="0" x2="10" y2="210" fill="none" stroke="gray" />
          <polyline points="1,200 10,210 19,200" fill="none" stroke="gray" />
        </svg>
</div>
      <div class="our-projects-samples__area">
        <div class="our-projects-samples__area--one">
          <our-projects-samples v-for="content in contents.slice(0,3)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"></our-projects-samples>
        </div>
        <div class="our-projects-samples__area--two">
          <our-projects-samples v-for="content in contents.slice(3,5)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"
          ></our-projects-samples>

        </div>
        <div class="our-projects-samples__area--three">
          <our-projects-samples
          v-for="content in contents.slice(5,8)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"></our-projects-samples>
        </div>
      </div>
    </div>
  </div>
    <br /><br /><br /><br />
    <div class="apply-resume">
      <p class="apply-resume__first">Don't miss this opportunity</p>
      <p class="apply-resume__second">You can handle it!</p>
      <button class="apply-resume__btn">APPLY RESUME</button>
    </div>
  </div>
</template>



<style scoped>

.our-projects-container {
  width: 100%;
  /*height: 100vh;*/
  position: relative;
}
@supports (-webkit-text-stroke: 2px #0000fd9f) {
  div.our-projects-container__text {
    color: transparent;
    -webkit-text-stroke: 1px #0000fd9f;
    text-shadow: none;
  }
}
.our-projects-container__text {
  /*width: 100%;*/
  color: white;
  text-shadow: 2px 2px #0000fd9f, -2px -2px #0000fd9f;
  height: 28.8rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  font-size: 13rem;
  position: absolute;
  left: 0;
  top: 0;
  z-index: -1;
}
.our-projects-container__text--first-section {
  transform: translateX(7.6rem);
}
.our-projects-sub-container {
  /* background-color: yellow; */
  width: 95%;
  height: 100%;
  margin: auto;
}
@media (min-width: 45rem){
.our-projects-headlines {
  margin-left: 2rem;
}}

@media (min-width: 65rem){
.our-projects-headlines {
  margin-left: 2.8rem;
}}

@media (min-width: 45rem){
.our-projects-title {
  font-size: 2rem;

  margin-bottom: -0.2rem;

}}

@media (min-width: 65rem){
.our-projects-title {
  font-size: 2.6rem;

  margin-bottom: -0.2rem;
}}

.our-projects-par {
  color: gray;

  font-size: 1rem;
}
.our-projects-samples {
  /* background-color: red; */
  display: flex;
  flex-direction: row;
}
.our-projects-samples__arrowdown {
  width: 1.5rem;
  margin-right: 1.3rem;
}
.arrowdown-icon {
  fill: gray;
}
.our-projects-samples__area {
  /* background-color: green; */
  width: 70%;
}

.our-projects-samples__area--one,
.our-projects-samples__area--two,
.our-projects-samples__area--three {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  margin-bottom: 2rem;
}
.apply-resume {
  width: 25rem;
  height: 10rem;
  text-align: center;

  margin: 3.5rem auto 6rem auto;
}
.apply-resume__first {
  font-size: 1.8rem;
  font-family: "DIN-Light";
  margin-bottom: -1.3rem;
}
.apply-resume__second {
  font-size: 1.8rem;
  font-family: "DIN-Light";
  margin-bottom: 0.3rem;
}
.apply-resume__btn {
  width: 9.2rem;
  height: 2.2rem;
  background-color: #0100fd;
  color: white;
  font-family: "DIN-Light";
  border: none;
}
.apply-resume__btn:hover {
  color: #0100fd;
  background-color: white;
  font-family: "DIN-Bold";
  border: 2px solid #0100fd;
}
</style>


