<script>
export default {
  data() {
    return {
      showFirstText: true,
    };
  },
  mounted() {
    setInterval(() => {
      this.showFirstText = !this.showFirstText;
    }, 5000);
  },
  methods: {},
};
</script>

<template>
  <div class="kandaidea-image">



    <div class="header">
      <div class="kandaidea-logo">
        <svg
        class="kandaidea-logo__icon"
          xmlns="http://www.w3.org/2000/svg"
          xml:space="preserve"
          width="4.16666in"
          height="0.694441in"
          version="1.1"
          style="
            shape-rendering: geometricPrecision;
            text-rendering: geometricPrecision;
            image-rendering: optimizeQuality;
            fill-rule: evenodd;
            clip-rule: evenodd;
          "
          viewBox="0 0 4166.66 694.44"
          xmlns:xlink="http://www.w3.org/1999/xlink"
        >
          <g id="__x0023_Layer_x0020_1">
            <metadata id="CorelCorpID_0Corel-Layer" />
            <g id="_2676963719376">
              <polygon
                class="fil0 str0"
                points="479.57,39 479.57,38.69 392.72,38.69 392.72,39 383.55,39 226.58,195.96 226.57,195.95 192.94,229.57 192.94,65.32 166.54,38.91 70.64,38.91 70.64,662.83 166.75,662.83 192.94,636.64 192.94,471.49 205.95,484.5 205.95,484.54 383.55,662.14 392.72,662.14 392.72,662.42 479.57,662.42 479.57,662.14 495.53,662.14 521.61,636.06 521.61,599.17 273.01,350.57 521.61,101.97 521.61,65.08 495.53,39 "
              />
              <polygon
                class="fil0 str0"
                points="2570.96,662.83 2693.26,662.83 2693.26,246.61 2570.96,246.61 "
              />
              <polygon
                class="fil0 str0"
                points="2570.96,175.26 2693.26,175.26 2693.26,37.16 2570.96,37.16 "
              />
              <polygon
                class="fil0 str0"
                points="1029.27,247.42 1029.27,662.45 1151.58,662.45 1151.58,369.72 1266.48,369.72 1314.69,419.12 1314.69,662.77 1410.66,662.77 1436.99,636.44 1436.99,369.34 1318.02,247.42 "
              />
              <path
                class="fil0 str0"
                d="M943.71 247.42l-263.03 0 -118.98 121.92 0 170.93 118.98 121.91 263.52 0 25.86 -25.86 -0.65 -241.71 0.74 -120.74 -26.45 -26.45zm-96.48 292.46l0 0 -115.01 0 -48.21 -49.4 0 -71.35 48.21 -49.4 115.04 0 -0.15 24.51 0.12 145.65z"
              />
              <path
                class="fil0 str0"
                d="M2359.78 247.42l-263.4 0 -118.98 121.92 0 170.93 118.98 121.91 263.52 0 25.86 -25.86 -0.65 -241.71 0.75 -121.12 -26.09 -26.08zm-96.85 292.46l0 0 -115.01 0 -48.21 -49.4 0 -71.35 48.21 -49.4 115.05 0 -0.16 24.51 0.12 145.65z"
              />
              <path
                class="fil0 str0"
                d="M4096.02 273.57l-26.16 -26.15 -263.33 0 -118.98 121.92 0 170.93 118.98 121.91 263.2 0 25.83 -25.82 0.34 0.34 -0.64 -242.09 0.75 -121.04zm-122.94 266.31l0 0 -115.01 0 -48.21 -49.4 0 -71.35 48.21 -49.4 115.04 0 -0.15 24.51 0.12 145.65z"
              />
              <path
                class="fil0 str0"
                d="M3330.41 247.42l-118.97 121.92 0 170.93 118.97 121.91 265.61 0 25.6 -25.6 0 -96.7 -122.78 0 123.2 -123.2 0 -44.39 -121.86 -124.87 -169.76 0zm23.84 264.07l0 0 -20.51 -21.02 0 -71.35 48.21 -49.4 66.68 0 23.41 23.98 -117.79 117.79z"
              />
              <path
                class="fil0 str0"
                d="M3034.27 38.69l0 208.73 -166.43 0 -118.97 121.92 0 170.93 118.97 121.91 25.78 0 118.66 0 119.01 -0.86 24.72 -24.71 0.57 0.57 0 -572.06 -26.43 -26.43 -95.87 0zm0 501.03l0 0 -114.89 0.16 -48.21 -49.4 0 -71.35 48.21 -49.4 114.89 0 0 170z"
              />
              <path
                class="fil0 str0"
                d="M1792.61 38.69l0 208.73 -166.43 0 -118.98 121.92 0 170.93 118.98 121.91 25.78 0 118.66 0 119.02 -0.86 25.28 -25.29 0 -571.33 -26.01 -26.02 -96.3 0zm0 501.03l0 0 -114.89 0.16 -48.21 -49.4 0 -71.35 48.21 -49.4 114.89 0 0 170z"
              />
            </g>
          </g>
        </svg>
      </div>
<div class="header-right__flex">
      <div class="lang">
        Choose Language: <a href="#" class="english"> En</a> /
        <a href="#" class="farsi">Fa</a>
      </div>

      <div class="menu-icon">
        <svg
          class="kandaidea-menu__icon"
          width="28"
          height="20"
          viewBox="0 0 28 20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M1.25 0.5H26.75L27.5 1.25V2.75L26.75 3.5H1.25L0.5 2.75V1.25L1.25 0.5ZM1.25 8.5H26.75L27.5 9.25V10.75L26.75 11.5H1.25L0.5 10.75V9.25L1.25 8.5ZM26.75 16.5H1.25L0.5 17.25V18.75L1.25 19.5H26.75L27.5 18.75V17.25L26.75 16.5Z"
            fill="white"
          />
          
        </svg>
      </div>
      </div>
    </div>

<div class="header-middle__container">
  <div class="header-middle__leftarroW">
<svg class="header-middle__leftarroW--icon" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" width="2.77777in" height="2.77777in" version="1.1" style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
viewBox="0 0 2777.77 2777.77"
 xmlns:xlink="http://www.w3.org/1999/xlink">

 <g id="__x0023_Layer_x0020_1">
  <metadata id="CorelCorpID_0Corel-Layer"/>
  <polygon class="fil0 str0" points="2229.62,2456.68 1160.33,1387.39 2228.39,319.33 2228.39,160.77 2116.27,48.64 2115.73,48.64 2115.72,48.64 1698.27,48.64 1636.1,48.64 1632.4,52.34 1632.38,52.34 1520.26,164.47 1520.26,164.48 872.66,812.09 872.66,970.65 954.17,1052.17 892.8,1113.55 816.63,1037.38 658.06,1037.38 545.93,1149.5 545.93,1244.29 545.93,1308.07 545.93,1477.43 545.93,1486.23 545.93,1636 658.06,1748.13 816.63,1748.13 898.15,1666.6 953.81,1722.26 870.71,1805.36 870.71,1963.93 982.83,2076.06 982.93,2076.06 1195.48,2288.61 1195.48,2291.86 1307.61,2403.98 1310.85,2403.98 1638.78,2731.91 1698.27,2731.91 1797.35,2731.91 2115.72,2731.91 2227.85,2619.78 2227.85,2617.02 2229.62,2615.25 "/>
 </g>
</svg>
</div>
  <div class="header-middle__text">CREATIVE<br>ENGINEERING<br>EXPERIENCE</div>
</div>



  <div class="header-text__container">
    <transition name="text">
      <div class="header-text header-text--first" v-if="showFirstText">


            <div class="pre">

                <svg class="r-and-d-icon" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M34 25.0477L29.0477 30H23.3909L28.3909 25H14V21H28.2953L23.2953 16H28.9522L33.9522 21H34L34 25.0477Z" stroke="white" stroke-width="0.5"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 38L8 44H4V13.3015L9.30151 8H38.6985L44 13.3015V32.6985L38.6985 38H14ZM12.3432 34L8 38.3432V14.9584L10.9584 12H37.0416L40 14.9584V31.0416L37.0416 34H12.3432Z" stroke="white" stroke-width="0.5"/>
                </svg>
               <div>
                    <div class="pre-rd-title">RESEARCH & DEVELOPMENT</div>
                    
                </div>

            </div>
            <!-- <div class="nums">
                <svg class="nums-icon-one" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M1 9.78677L9.78677 1H22.2132L31 9.78677V32H32V9.37256L22.6274 0H9.37256L0 9.37256V32H1V9.78677Z" fill="#fff"/>
                    <path d="M17.4766 25H16.0703V9.625L11.4297 11.3477V10.0352L17.2422 7.87891H17.4766V25Z" fill="#fff"/>
                </svg>
            </div> -->
            <div class="line"></div>
            <!-- <div class="nums">
                <svg class="nums-icon" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M0 9.37256L9.37256 0H22.6274L32 9.37256V22.6274L22.6274 32H9.37261L0 22.6274V9.37256Z" fill="white"/>
                    <path d="M14.0664 15.707H15.5195C16.3242 15.707 17.0273 15.5664 17.6289 15.2852C18.2305 14.9961 18.6875 14.6055 19 14.1133C19.3203 13.6133 19.4805 13.0391 19.4805 12.3906C19.4805 11.2969 19.1719 10.4414 18.5547 9.82422C17.9375 9.20703 17.0508 8.89844 15.8945 8.89844C14.8008 8.89844 13.9023 9.22266 13.1992 9.87109C12.5039 10.5117 12.1562 11.3594 12.1562 12.4141H10.75C10.75 11.5312 10.9727 10.7266 11.418 10C11.8633 9.26562 12.4805 8.69922 13.2695 8.30078C14.0586 7.90234 14.9336 7.70312 15.8945 7.70312C17.4414 7.70312 18.6602 8.125 19.5508 8.96875C20.4414 9.8125 20.8867 10.9688 20.8867 12.4375C20.8867 13.2578 20.625 14.0156 20.1016 14.7109C19.5859 15.3984 18.875 15.9141 17.9688 16.2578C19.0312 16.5547 19.8359 17.0664 20.3828 17.793C20.9297 18.5117 21.2031 19.3711 21.2031 20.3711C21.2031 21.832 20.7266 23.0078 19.7734 23.8984C18.8203 24.7891 17.5469 25.2344 15.9531 25.2344C14.9375 25.2344 14.0039 25.0312 13.1523 24.625C12.3086 24.2188 11.6523 23.6523 11.1836 22.9258C10.7227 22.1914 10.4922 21.3398 10.4922 20.3711H11.8984C11.8984 21.457 12.2773 22.3438 13.0352 23.0312C13.793 23.7109 14.7656 24.0508 15.9531 24.0508C17.1641 24.0508 18.1055 23.7422 18.7773 23.125C19.457 22.5 19.7969 21.5977 19.7969 20.418C19.7969 19.2773 19.4297 18.4062 18.6953 17.8047C17.9688 17.2031 16.8945 16.9023 15.4727 16.9023H14.0664V15.707Z" fill="black"/>
                </svg>

            </div>
            <div class="arrowdown">
                <svg class="nums-icon-d" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M22.6274 -4.09688e-07L32 9.37256L32 22.6274L22.6274 32L9.3726 32L-9.89075e-07 22.6274L-4.0969e-07 9.37261L9.37261 -9.89075e-07L22.6274 -4.09688e-07Z" fill="#0000FF"/>
                    <path d="M24 13L16 21L8 13" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </div> -->
            <div class="post" >
<svg class="post-ss-icon" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M20.6863 16L16 20.6863V27.3137L20.6863 32H27.3137L32 27.3137V20.6863L27.3137 16H20.6863ZM20 25.6569V22.3431L22.3431 20H25.6569L28 22.3431V25.6569L25.6569 28H22.3431L20 25.6569Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M12.5982 7.11755L7.11755 12.5982L9.83032 17.5785L9.43981 18.5212L4 20.1246V27.8754L9.43981 29.4788L9.83032 30.4215L7.11755 35.4018L12.5982 40.8824L17.5785 38.1697L18.5212 38.5602L20.1246 44H27.8754L29.4788 38.5602L30.4215 38.1697L35.4018 40.8824L40.8824 35.4018L38.1697 30.4215L38.5602 29.4788L44 27.8754V20.1246L38.5602 18.5212L38.1697 17.5785L40.8825 12.5982L35.4018 7.11755L30.4215 9.83032L29.4788 9.43981L27.8754 4H20.1246L18.5212 9.43981L17.5785 9.83032L12.5982 7.11755ZM14.2572 17.3435L12.4039 21.8177L8 23.1158V24.8842L12.4039 26.1823L14.2572 30.6565L12.061 34.6885L13.3115 35.939L17.3435 33.7428L21.8177 35.5961L23.1158 40H24.8842L26.1823 35.5961L30.6565 33.7428L34.6885 35.939L35.939 34.6885L33.7428 30.6565L35.5961 26.1823L40 24.8842V23.1158L35.5961 21.8177L33.7428 17.3435L35.939 13.3115L34.6885 12.061L30.6565 14.2572L26.1823 12.4039L24.8842 8H23.1158L21.8177 12.4039L17.3435 14.2572L13.3115 12.061L12.061 13.3115L14.2572 17.3435Z" fill="white"/>
</svg>

              <div> 
                 <div class="post-ss-title">SERVICES & SOLUTIONS</div>
                <div class="post-ss-subtitle">Over 15 years of experience in engineering services consultiancy and taking advantage of expert  human resources, Kanda Idea provides awide range of services and solutions and became one of the leading consultants in the region.</div></div>
              
            </div>

      </div>


      <div class="header-text header-text--second" v-else>


          <div class="pre">
            <svg class="ss-icon" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M20.6863 16L16 20.6863V27.3137L20.6863 32H27.3137L32 27.3137V20.6863L27.3137 16H20.6863ZM20 25.6569V22.3431L22.3431 20H25.6569L28 22.3431V25.6569L25.6569 28H22.3431L20 25.6569Z" stroke="white" stroke-width="0.5"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M12.5982 7.11755L7.11755 12.5982L9.83032 17.5785L9.43981 18.5212L4 20.1246V27.8754L9.43981 29.4788L9.83032 30.4215L7.11755 35.4018L12.5982 40.8824L17.5785 38.1697L18.5212 38.5602L20.1246 44H27.8754L29.4788 38.5602L30.4215 38.1697L35.4018 40.8824L40.8824 35.4018L38.1697 30.4215L38.5602 29.4788L44 27.8754V20.1246L38.5602 18.5212L38.1697 17.5785L40.8825 12.5982L35.4018 7.11755L30.4215 9.83032L29.4788 9.43981L27.8754 4H20.1246L18.5212 9.43981L17.5785 9.83032L12.5982 7.11755ZM14.2572 17.3435L12.4039 21.8177L8 23.1158V24.8842L12.4039 26.1823L14.2572 30.6565L12.061 34.6885L13.3115 35.939L17.3435 33.7428L21.8177 35.5961L23.1158 40H24.8842L26.1823 35.5961L30.6565 33.7428L34.6885 35.939L35.939 34.6885L33.7428 30.6565L35.5961 26.1823L40 24.8842V23.1158L35.5961 21.8177L33.7428 17.3435L35.939 13.3115L34.6885 12.061L30.6565 14.2572L26.1823 12.4039L24.8842 8H23.1158L21.8177 12.4039L17.3435 14.2572L13.3115 12.061L12.061 13.3115L14.2572 17.3435Z" stroke="white" stroke-width="0.5"/>
</svg>

              <div class="pre-ss-title">SERVICES & SOLUTIONS</div>
            
          </div>
          <!-- <div class="nums">
              <svg class="nums-icon" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M0 9.37256L9.37256 0H22.6274L32 9.37256V22.6274L22.6274 32H9.37261L0 22.6274V9.37256Z" fill="white"/>
                  <path d="M14.0664 15.707H15.5195C16.3242 15.707 17.0273 15.5664 17.6289 15.2852C18.2305 14.9961 18.6875 14.6055 19 14.1133C19.3203 13.6133 19.4805 13.0391 19.4805 12.3906C19.4805 11.2969 19.1719 10.4414 18.5547 9.82422C17.9375 9.20703 17.0508 8.89844 15.8945 8.89844C14.8008 8.89844 13.9023 9.22266 13.1992 9.87109C12.5039 10.5117 12.1562 11.3594 12.1562 12.4141H10.75C10.75 11.5312 10.9727 10.7266 11.418 10C11.8633 9.26562 12.4805 8.69922 13.2695 8.30078C14.0586 7.90234 14.9336 7.70312 15.8945 7.70312C17.4414 7.70312 18.6602 8.125 19.5508 8.96875C20.4414 9.8125 20.8867 10.9688 20.8867 12.4375C20.8867 13.2578 20.625 14.0156 20.1016 14.7109C19.5859 15.3984 18.875 15.9141 17.9688 16.2578C19.0312 16.5547 19.8359 17.0664 20.3828 17.793C20.9297 18.5117 21.2031 19.3711 21.2031 20.3711C21.2031 21.832 20.7266 23.0078 19.7734 23.8984C18.8203 24.7891 17.5469 25.2344 15.9531 25.2344C14.9375 25.2344 14.0039 25.0312 13.1523 24.625C12.3086 24.2188 11.6523 23.6523 11.1836 22.9258C10.7227 22.1914 10.4922 21.3398 10.4922 20.3711H11.8984C11.8984 21.457 12.2773 22.3438 13.0352 23.0312C13.793 23.7109 14.7656 24.0508 15.9531 24.0508C17.1641 24.0508 18.1055 23.7422 18.7773 23.125C19.457 22.5 19.7969 21.5977 19.7969 20.418C19.7969 19.2773 19.4297 18.4062 18.6953 17.8047C17.9688 17.2031 16.8945 16.9023 15.4727 16.9023H14.0664V15.707Z" fill="black"/>
              </svg>

          </div> -->
          <div class="line"></div>

          <!-- <div class="nums">
              <svg class="nums-icon-one" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1 9.78677L9.78677 1H22.2132L31 9.78677V32H32V9.37256L22.6274 0H9.37256L0 9.37256V32H1V9.78677Z" fill="#fff"/>
                  <path d="M17.4766 25H16.0703V9.625L11.4297 11.3477V10.0352L17.2422 7.87891H17.4766V25Z" fill="#fff"/>
              </svg>
          </div> -->
          <!-- <div class="arrowdown">
              <svg class="nums-icon-d" width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M22.6274 -4.09688e-07L32 9.37256L32 22.6274L22.6274 32L9.3726 32L-9.89075e-07 22.6274L-4.0969e-07 9.37261L9.37261 -9.89075e-07L22.6274 -4.09688e-07Z" fill="#0000FF"/>
                  <path d="M24 13L16 21L8 13" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
          </div> -->
          <div class="post">

            <svg class="post-r-and-d-icon" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M34 25.0477L29.0477 30H23.3909L28.3909 25H14V21H28.2953L23.2953 16H28.9522L33.9522 21H34L34 25.0477Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M14 38L8 44H4V13.3015L9.30151 8H38.6985L44 13.3015V32.6985L38.6985 38H14ZM12.3432 34L8 38.3432V14.9584L10.9584 12H37.0416L40 14.9584V31.0416L37.0416 34H12.3432Z" fill="white"/>
></svg>

               <div>
                    <div class="post-and-title">RESEARCH & DEVELOPMENT</div>
                    <div class="post-and-subtitle">ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
                    </div>
               </div>


          </div>
         </div>

  </transition>
</div>











  </div>
</template>


<style scoped>
@media (min-width: 45rem){
.kandaidea-image {
  position: relative;
  top: 0;
  right: 0;
  margin: 0;
  width: 100vw;
  height: 100vh;
  background-image: url("/img/kenid.webp") ;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
}
@media (min-width: 64rem){
.kandaidea-image {
  position: relative;
  margin: 0;
  width: 100vw;
  height: 100vh;
  background-image: url("/img/kenid.webp");
  background-repeat: no-repeat;
  background-size: cover;
}}


.line{
  width: 100%;
  height: 10px;
  border-top:3px solid white;
  margin: 1rem 0 1rem 0;
}

.header {
  width: 92%;
  margin: auto;
  padding-top: 2rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
@media (min-width: 45rem){
.kandaidea-logo__icon {
  fill: white;
  width: 12rem;
}}

@media (min-width: 64rem){
.kandaidea-logo__icon {
  fill: white;
  width: 17rem;
}}

.header-right__flex {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-self: center;
}
.kandaidea-menu__icon {
  margin-left: 2rem;
  margin-right: 1rem;
}
a:link,
.lang {
  text-decoration: none;
  color: white;
  font-size: 1rem;
  line-height: 1.7;
  font-family: "DIN-Light";
}

a:visited {
  text-decoration: none;
  color: white;
  font-family: "DIN-Bold";
}

a:hover {
  text-decoration: none;
  font-family: "DIN-Bold";
}

a:active {
  text-decoration: none;
}
@media (min-width: 45rem){
.kandaidea-logo__icon {
  fill: white;
  width: 12rem;
}}
@media (min-width: 65rem){
.kandaidea-logo__icon {
  fill: white;
  width: 17rem;
}}

@media (min-width: 45rem){
.header-middle__container {
  
  width: 15rem;
  height: 15rem;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}}


@media (min-width: 65rem){
.header-middle__container {
  margin-left: 2rem;
  width: 15rem;
  height: 15rem;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}}


@media (min-width: 45rem){
.header-middle__text {
  color: white;
  font-size: 1.2rem;
  line-height: 1.2;
}}
@media (min-width: 65rem){
.header-middle__text {
  color: white;
  font-size: 2rem;
   line-height: 1.4;
}}

@media (min-width: 45rem){
.header-middle__leftarroW--icon {
  fill: rgba(145, 145, 145, 0.062);
  stroke: white;
  stroke-width: 5;
  width: 7rem;
  margin-right: -5rem;
}} 

@media (min-width: 65rem){
.header-middle__leftarroW--icon {
  fill: rgba(145, 145, 145, 0.062);
  stroke: white;
  stroke-width: 5;
  width: 10rem;
  margin-right: -7rem;
}}

@media (min-width: 45rem){
.header-text__container {
  height: 20%;
  width: 100vw;
  color: white;
  font-size: 1rem;
  position: absolute;
  left: 0;
  bottom: 7rem;
 
}}

@media (min-width: 65rem){
.header-text__container {
  height: 20%;
  width: 100vw;
  color: white;
  font-size: 1.5rem;
  position: absolute;
  left: 0;
  bottom: 10rem;
 
}}
.text-enter-active {
  animation: animated-text 2s forwards;
}
.text-leave-active {
  display: none;
}
@keyframes animated-text {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.pre,
.post {
  display: flex;
  flex-direction: row;
  margin-left: 3rem;
  justify-content: flex-start;
  align-items: center;
}

@media (min-width: 45rem){
.r-and-d-icon,
.ss-icon {
  width: 3rem;
  height: 2rem;
  align-self: center;
}}

@media (min-width: 65rem){
.r-and-d-icon,
.ss-icon {
  width: 4rem;
  height: 2.5rem;
  align-self: center;
}}

@media (min-width: 45rem){
.post-r-and-d-icon,
.post-ss-icon {
  width: 3rem;
  height: 3rem;
  /* align-self: center; */
  margin-top: -3.2rem;
}}

@media (min-width: 65rem){
.post-r-and-d-icon,
.post-ss-icon {
  width: 4rem;
  height: 2.5rem;
  align-self: center;
  margin-top: -3.2rem;
}}

@media (min-width: 45rem){
.pre-rd-title,
.pre-ss-title {
  font-size: 1.5rem;
  font-family: "DIN-Bold";
  -webkit-text-stroke: 1px white;
  color: rgba(255, 255, 0, 0.042);
}}

@media (min-width: 65rem){
.pre-rd-title,
.pre-ss-title {
  font-size: 1.8rem;
  font-family: "DIN-Bold";
  -webkit-text-stroke: 1px white;

  color: rgba(255, 255, 0, 0.042);
}}

.post-and-subtitle,
.post-ss-subtitle {
  font-size: 1rem;
  font-family: "DIN-Light";
  margin-top: 0.6rem;
  line-height: 1.4;
}

/* .nums-icon-d{
  position: relative;
  right: 3rem;
  bottom:1rem;
  margin-bottom:-.2
}
.nums-icon{
    position: relative;
  right: 3rem;
  bottom:3rem;
  margin-bottom:-.2
}
.nums-icon-one {
  position: relative;
  right: 3rem;
  bottom:5.6rem;
  margin-bottom: -0.3em;
} */
</style>