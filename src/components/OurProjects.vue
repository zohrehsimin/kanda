<script>
import OurProjectsSamples from './OurProjectsSamples.vue';

    export default {
        components: {
            OurProjectsSamples
            
        },
        data(){
          return {
            contents : [{src:'/img/1.png', text: 'xxx'},{src:'/img/2.png',text:'yyy'},{src:'/img/3.jpg', text:'www'},{src:'/img/4.jpg',text : 'aaa'},{src:'/img/5.png',text:'bbb'},{src:'/img/6.jpg', text:'ccc'},{src:'/img/7.jpg', text:'ddd'}, {src:'/img/8.png',text:'fff'}]
          }
        }
        
    }
</script>

<template>
  <div class="ourprojects-container">
    <div class="ourprojects-headlines">
      <p class="ourprojects-title">OUR PROJECTS</p>
      <p class="ourprojects-par">
        Discover the next inspiring talks in industry.
      </p>
    </div>
    <div class="ourprojects-samples">
      <div class="ourprojects-samples__arrowdown">
        <svg
          class="arrowdown-icon"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          viewBox="0 0 20 20"
        >
          <title>arrow-thin-down</title>
          <path
            d="M9 16.172l-6.071-6.071-1.414 1.414 8.485 8.485 8.485-8.485-1.414-1.414-6.071 6.071v-16.172h-2z"
          ></path>
        </svg>
      </div>

      <div class="ourprojects-samples__area">
        <div class="ourprojects-samples__area--one">
          <!-- <our-projects-samples></our-projects-samples
          ><our-projects-samples></our-projects-samples
          ><our-projects-samples></our-projects-samples> -->
          <our-projects-samples v-for="content in contents.slice(0,3)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"></our-projects-samples>
        </div>
        <div class="ourprojects-samples__area--two">
          <our-projects-samples v-for="content in contents.slice(3,5)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"
          ></our-projects-samples>

        </div>
        <div class="ourprojects-samples__area--three">
          <our-projects-samples
          v-for="content in contents.slice(5,8)"
          :key="content.text"
          :sample-image-src="content.src"
          :sample-text="content.text"></our-projects-samples>
        </div>
      </div>
    </div>
  </div>
</template>



<style scoped>
.ourprojects-container {
  /* background-color: yellow; */
  width: 96vw;
  height: 115vh;
  margin: auto;
}
.ourprojects-headlines {
  margin-left: 2.8rem;
}
.ourprojects-title {
  font-size: 2.6rem;
  font-weight: bold;
  margin-bottom: -1rem;
}
.ourprojects-par {
  color: gray;

  font-size: 1.1rem;
}
.ourprojects-samples {
  /* background-color: red; */
  display: flex;
  flex-direction: row;
}
.ourprojects-samples__arrowdown {
  /* background-color: pink; */
  width: 1.5rem;
  margin-right: 1.3rem;
}
.arrowdown-icon {
  fill: gray;
}
.ourprojects-samples__area {
  /* background-color: green; */
  width: 70%;
}

.ourprojects-samples__area--one,.ourprojects-samples__area--two,.ourprojects-samples__area--three{display: flex;
flex-direction: row;
align-items: flex-start;
margin-bottom: 2rem;

}
</style>