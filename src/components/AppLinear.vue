<script>
export default{

}
</script>
 <template>
    <div class="linear-bg">
        <div class="video-cont container">
    <div class="videos d-flex row-cols-3 justify-content-between">
        <div class="col"><img src="../assets/service6-2x.jpg" alt="video"><div class="position"><p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
<h3>Heavy workout</h3><h4>Push your limits</h4></div></div>
        <div class="col"><img src="../assets/box1-2x.jpg" alt="video"><div class="position"><p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
<h3>New gym apparel</h3><h4>Look good, feel good</h4></div></div>
        <div class="col"><img src="../assets/box3-2x.jpg" alt="video"><div class="position"><p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
<h3>Team training</h3><h4>Find a partner</h4></div></div>
    </div>
</div><div class="caption text-center">
        <h1>"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</h1>
        <p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
        <div class="d-flex avatar align-items-center justify-content-center">
            <img src="../assets/avatar-1-2x.jpg" alt="Brandon">
            <p class="color-w">Bran Jhonson</p>
            <p>Las Vegas</p>
        </div>
    </div>
    </div>
    
 </template>
  <style lang="scss" scoped>
.linear-bg{
    height: 900px;
    background-image: linear-gradient(to bottom right, blue, purple ,red);
}
i{
    color:#FFF941;
    margin: -2px;
}
h3{
    color: white;
}
h4{
    color:white;
}
.color-w{
    color: white;
}
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
    width: 100%;
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
.col{
    margin-top: -100px;
    width: 400px;
}
.positon{
    position: relative;
    top: -100px;
}
.caption{
    height:400px;
    h1{
        color: white;
        margin-bottom: 100px;
    }
}
.avatar{
    p{
        margin-left: 20px;
        font-weight: bold;
    }
    img{
        border-radius: 100%;
        width: 80px;
    }

}
</style>