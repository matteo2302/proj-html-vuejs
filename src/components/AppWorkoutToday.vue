<script>
export default{
 
}
</script>
<template>
    <div class="banner-bg">
        <div class="linear-bg  flex-column  d-flex justify-content-center align-items-center">
            <button class="play-btn"><i class="fa-solid fa-play"></i></button>
            <h2>Chest workout of the day</h2>
            <h3>November 15th, 2019</h3>
            <a href="#">View all videos <i class="fa-solid fa-arrow-right"></i></a>
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
h2{
    color: white;
}
h3{
    color: #FFF941 ;
}
.play-btn{
    padding: 40px 46px;
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