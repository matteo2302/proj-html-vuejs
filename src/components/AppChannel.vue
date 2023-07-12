<script>
export default {};
</script>
<template>
    <div class="channel-cont d-flex">
        <img src="../assets/service15-2x.jpg" alt="abs" />
        <button class="play-btn"><i class="fa-solid fa-play"></i></button>
        <div class="d-flex flex-column justify-content-center">
            <h4>Tune up your workouts</h4>
            <h1>The best health & fitness advice Online</h1>
            <div class="channel my-4 d-flex">
                <img src="../assets/unnamed.jpg" alt="Channel image">
                <div><p class="color-g">ThemeFusion</p>
                <div class="d-flex">
                    <p class="bg-red px-1"><i class="fa-brands fa-youtube"></i>YouTube</p>
                    <p class="bg-n px-1">999+</p>
                </div></div>
                
            </div>
            <p class="channel-des">Arcu eu facilisi ut quisque placerat habitant. Magna semper mauris, venenatis, leo interger sit pellentesque
            </p>
            <button class="channel-btn"><i class="fa-brands fa-youtube"></i> visit my YouTube channel</button>
        </div>
    </div>
    <div class="video-cont my-5 container">
        <div class="d-flex align-items-center justify-content-between">
            <h3>Featured playlist</h3>
            <a href="#">View all video ></a>
        </div>
        <div class="videos d-flex row-cols-3 justify-content-between text-center">
            <div class="col">
                <img src="../assets/video2-2x.jpg" alt="video" />
                <h4>Thighs & glute workout</h4>
                <a href="#">Increase your mobility</a>
                <!-- <button class="play-btn"><i class="fa-solid fa-play"></i></button> -->
            </div>
            <div class="col">
                <img src="../assets/video7-2x.jpg" alt="video" />
                <h4>Lift, firm & perk up</h4>
                <a href="#">Feel young again</a>
                <!-- <button class="play-btn"><i class="fa-solid fa-play"></i></button> -->
            </div>
            <div class="col">
                <img src="../assets/video9-2x.jpg" alt="video" />
                <h4>Slim & trim you waist</h4>
                <a href="#">Shed those extra pounds</a>
                <!-- <button class="play-btn"><i class="fa-solid fa-play"></i></button> -->
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.channel-cont {
    height: 650px;
    width: 100%;
h4{
    color: #4154ff;
}
    img {
        position: relative;
        top: -35px;
    }
}
.bg-red{
    background-color: red;
    color: white;


}
.bg-n{border: 1px solid #98939F;}
.channel {
    img {
        height: 40px;
        width: 40px;
        top: 0;
    }

}

.play-btn {
    right: 25%;
    top: 35%;
    position: relative;
    padding: 40px 46px;
    height: 107px;
    border-radius: 100%;
    border: none;
    background-color: white;

    i {
        color: #4154ff;
    }
}

img {
    border-bottom-right-radius: 25px;
}

.videos {
    height: 300px;
    margin-bottom: 100px;

    img {
        width: 100%;
    }
}

a {
    color: black;
}
.color-g{
    color: #98939F;
    margin-bottom: 0;
    font-size: 12px;
}
.channel-des{
    font-size: 20px;
    color: #98939F;
}
.channel-btn{
    width: 250px;
    padding: 20px 20px;
    background-color: red;
    color: white;
    border-radius: 50px;
    border: none;
}
.col{
    width: 400px;
    a{
        font-weight: bold;
        color: #4154ff;
       
    }
    h4{
        margin-top: 20px;
    }
    button{
        top: -250px;
        right: 75px;
    }
}
</style>
