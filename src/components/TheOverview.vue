<script>
export default {};
</script>

<template>
  <!-- /* -------------------------------------first part--------------------------------------------*/ -->
  <div class="first-part__flex">

    <div class="firt-part__item">
      <div class="first-part__item--arrowdown">
       
<svg class="arrowdown-icon" viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg" xmlns:bx="https://boxy-svg.com">
  <path d="M 281.278 37.46 H 729.781 L 719.781 -3.091 L 753.278 44.909 L 719.781 92.909 L 729.781 52.358 H 281.278 V 37.46 Z" style="stroke-width: 4px;" transform="matrix(-0.000067, 1, -1, -0.000067, 255.988098, -254.13913)" bx:shape="arrow 281.278 -3.091 472 96 14.898 33.497 10 1@911ae820" bx:origin="0.501 0.499998"/>
</svg>

  
      </div>
      <article class="first-part__item--article">
        <p class="first-part__item--article-title">OVERVIEW</p>
        <p class="first-part__item--article-header">THE CONFLUENCE OF ENGINEERING & CRIATIVITY</p>
        <p class="first-part__item--article-par">
          Kanda Idea is a leading Iranian company with a long-term<br> successful
          experiance in providing technology-based engineering.<br> monitoring
          (supervising) and management services in mega-<br>projects, enterprises
          and the public sector.
        </p>
      </article>
    </div>

    <div class="first-part__svg">
      <svg
        class="overview-icon"
        width="110"
        height="50"
        viewBox="0 0 110 50"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g clip-path="url(#clip0)">
          <path
            d="M88 0.17157L109.414 21.5858L106.586 24.4142L88 5.82843L77 16.8284L69 8.82843L46 31.8284L22.5858 8.41421L25.4142 5.58578L46 26.1716L69 3.17157L77 11.1716L88 0.17157Z"
            fill="#0000FF"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M9.3725 18L0 27.3725V42.7329L12.4133 37.8582L7.15537 50H22.6275L32 40.6273V27.3725L22.6275 18H9.3725ZM4 29.0294L11.0294 22H20.9706L28 29.0294V38.9704L20.9706 46H13.2465L14.5456 43H19.7278L25 37.7278V30.2719L19.7278 25H12.2722L7 30.2719V35.6867L4 36.8648V29.0294ZM11 34.1159L13.7523 33.035L17.3373 36.5534L16.2778 39H18.071L21 36.071V31.9288L18.071 29H13.929L11 31.9288V34.1159Z"
            fill="#0000FF"
          />
          <path d="M39 50V30.4853L43 34.4853V50H39Z" fill="#0000FF" />
          <path d="M53 50V30.4853L57 26.4853V50H53Z" fill="#0000FF" />
          <path
            d="M69 14.4853L71 16.4853V50H67V16.4853L69 14.4853Z"
            fill="#0000FF"
          />
          <path d="M81 50V18.4853L85 14.4853V50H81Z" fill="#0000FF" />
          <path d="M95 50V18.4853L99 22.4853V50H95Z" fill="#0000FF" />
        </g>
        <defs>
          <clipPath id="clip0">
            <rect width="110" height="50" fill="white" />
          </clipPath>
        </defs>
        <!-- Code injected by live-server -->
        
      </svg>
    </div>
  </div>
  <!-- /* -------------------------------------second- part--------------------------------------------*/ -->
  <div class="second-part__flex">
    <div class="statistics">
      <h2>530,000</h2>
      <h4>M/H WORK</h4>
    </div>
    <div class="statistics">
      <h2>200,000</h2>
      <h4>Lines of Code</h4>
    </div>
    <div class="statistics">
      <h2>75</h2>
      <h4>Fields</h4>
      <h5>WORDLWIDE</h5>
    </div>
    <div class="statistics">
      <h2>45</h2>
      <h4>Active</h4>

      <h5>& COMPLETED PROJECTS</h5>
    </div>
    <div class="statistics">
      <h2>150</h2>
      <h4>Personnel</h4>
      <h5>Full-Time & <br>Part-Time Colleagues</h5>
    </div>
    <div class="statistics">
      <h2>30</h2>
      <h4>Master</h4>
      <h5>and PhD STUDENTS</h5>
    </div>
  </div>
</template>



<style  scoped>
.first-part__flex {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  /* background-color: red; */
  width:96vw;
  height: 46vh;
  margin: auto;
  margin-bottom: 2rem;
  margin-top: 1rem;
  
}
.firt-part__item {
    /* background-color: rebeccapurple; */
  width: 46%;
  height: 38vh;
  padding-top: 1rem;
  display: flex;
  flex-direction: row;
  

}
.first-part__item--arrowdown{
/* background-color: burlywood; */
width: 2.5rem;
padding-top: 2.8rem;
margin-right: 1.3rem;
}
.arrowdown-icon{

  width: 2rem;
    fill: gray;
}

.first-part__item--article-title{
    font-size: 2.6rem;
    margin-bottom: -1rem;
}
.first-part__item--article-header {
    font-size: 2rem;
  color: #0100fd;
  font-weight: 100;
  letter-spacing: 3px;
  margin-bottom: -.5rem;
}
.first-part__item--article-par{
    color: gray;
    /* font-weight: 100; */
    font-size: 1.1rem;
    
}


.first-part__svg{
     width: 46%;
  height: 38vh;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 3rem;

  
  }
.overview-icon{
    width: 28rem;
    height: 14rem;

}
.second-part__flex {
/* background-color: yellow; */
  width: 96vw;
  margin: auto;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.statistics{
    width: 10%;
    /* background-color: palevioletred; */
    

}
h2,h4{
    margin-bottom: -1.3rem;
}
h2 {
  color: #0100fd;
  font-weight: 900;
}

h4{
    color: gray;

}
h5 {
  color: gray;
  font-weight: 100;
}

</style>