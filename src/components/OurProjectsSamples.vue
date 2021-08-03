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
.samples-item{
   position : relative;
  background-repeat: no-repeat;
  background-size: cover;
    width: 15rem;
    height: 15rem;
    margin-right: 2rem;
}
img{
    width: 15rem;
    height: 15rem;
}
.sample-text{
    position : absolute;
    top: 0;
    left: 0;
    z-index : 1
}

</style>