<script>

    export default {
        props : ['sampleImageSrc', 'sampleText']
    }
</script>

<template>
    <div>
         <div class="samples-item">
             <img :src="sampleImageSrc" alt="Not Loaded">
             <div class="sample-text">{{sampleText}}</div>
         </div>
    </div>
</template>



<style scoped>
@media (min-width: 45rem){
.samples-item{
   position : relative;
  background-repeat: no-repeat;
  background-size: cover;
    width: 11rem;
    height: 11rem;
    margin-right: 2rem;

}
}

@media (min-width: 64rem){
.samples-item{
   position : relative;
  background-repeat: no-repeat;
  background-size: cover;
    width: 15rem;
    height: 15rem;
    margin-right: 2rem;

}
}

@media (min-width: 45rem){
img{
    width: 11rem;
    height: 11rem; 

}
}

@media (min-width: 64rem){
img{
    width: 15rem;
    height: 15rem; 

}
}

.sample-text{
    position : absolute;
    top: 0;
    left: 0;
    z-index : 1;
    font-size : 1.4rem;
    font-family: "DIN-Light";
    padding: 1.5rem 0 0 1.2rem;
    color: white;
    text-shadow: 4px 4px 2px rgba(150, 150, 150, 1);

}

</style>