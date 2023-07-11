<script>
export default{}
</script>
<template>
<div class="channel-cont d-flex">
    <img src="../assets/service15-2x.jpg" alt="abs">
    <div>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum inventore, quidem ipsum voluptate, officiis quia totam blanditiis in assumenda magni consequuntur molestiae. Delectus error labore iusto, velit suscipit adipisci! Autem!</div>
</div>
<div class="video-cont container">
    <h3>Featured playlist</h3>
    <div class="videos d-flex row-cols-3 g-2 text-center">
        <div class="col"><img src="../assets/video2-2x.jpg" alt="video"><h4>Thighs & glute workout</h4><a href="#">Increase your mobility</a></div>
        <div class="col"><img src="../assets/video7-2x.jpg" alt="video"><h4>Lift, firm & perk up</h4><a href="#">Feel young again</a></div>
        <div class="col"><img src="../assets/video9-2x.jpg" alt="video"><h4>Slim & trim you waist</h4><a href="#">Shed those extra pounds</a></div>
    </div>
</div>
</template>
<style lang="scss" scooped>
.channel-cont{
    height: 500px;
    
    img{
        width: 50%;
        position: relative;
        top:-35px;
    }
}
img{
    border-bottom-right-radius: 25px;
}
.videos{
    height: 300px;
    margin-bottom: 100px;
    img{
        width: 100%;
    }
}
</style>