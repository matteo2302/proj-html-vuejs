<script>
export default{
}
</script>
<template>
<div class="latest-cont my-5 container">
    <div class="d-flex align-items-center justify-content-between"><h3>Latest Article</h3> <a href="#">Read all video ></a></div>    
    <div class="videos d-flex row-cols-3 g-2">
        <div class="col"><img src="../assets/blog4-2x.jpg" alt="video"><h4 class="ps-3">The best prootein shake</h4><a class="ps-3" href="#">By admin | November 26th,2019| Gym</a></div>
        <div class="col"><img src="../assets/blog1-2x.jpg" alt="video"><h4 class="ps-3">Ultimate Arms workout</h4><a class="ps-3" href="#">By admin | November 26th,2019| Gym</a></div>
        <div class="col"><img src="../assets/blog3-2x.jpg" alt="video"><h4 class="ps-3">New gears avaible now</h4><a class="ps-3" href="#">By admin | November 26th,2019| Gym</a></div>
    </div>
</div>
</template>
<style scoped>
.latest-cont{
    height: 450px;
}
.videos{
    height: 300px;
    margin-bottom: 100px;
    img{
        width: 100%;
    }
}
a{
    color: black;
}
</style>