<script>
export default{
 
}
</script>
<template>
    <div class="banner-bg">
        <div class="linear-bg  flex-column  d-flex justify-content-center align-items-center">
            <button class="play-btn"><i class="fa-solid fa-play"></i></button>
            <h1 class="my-3">Chest workout of the day</h1>
            <h3 class="my-3">November 15th, 2019</h3>
            <a  class="my-3" href="#">View all videos <i class="fa-solid fa-arrow-right"></i></a>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.banner-bg{
    background-image: url(../assets/banner14-2x.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    height: 700px;
}
h1{
    color: white;
    font-size: 50px;
}
h3{
    color: #FFF941 ;
}
.play-btn{
    padding: 38px 44px;
    border-radius: 100%;
    border: none;
    i{
        color: #4154ff;
    }
}
.linear-bg{
    height: 700px;
    background-image: linear-gradient(to bottom right, rgba(0, 0, 255, 0.300), rgba(128, 0, 128, 0.300) ,rgba(255, 0, 0, 0.300));
}
</style>