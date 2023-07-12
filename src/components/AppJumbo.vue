<script>
import AppLinear from './AppLinear.vue';
export default{
    components:{AppLinear}
}</script>

<template> 
<div class="jumbotron"> 
<div class="shadow">
    <div class="d-flex container h-100 row-cols-2 align-items-center">
        
        <div class="col-9">
            <h4>Certified fitness professional</h4>
            <h1>Take control of your health</h1>
            <p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
            <p>Curabitur non nulla sit amet nisl tempus quis ac lectus dolor sit amet.</p>
            <div>
                <button class="channel"><a href="#"><i class="fa-brands fa-youtube"></i> Visit my YouTube vhannel</a></button>
                <button><a href="#">Buy Avada today <i class="fa-solid fa-arrow-right"></i></a></button>
            </div>
        </div>
        <div class="col-3 d-flex justify-content-center"><button class="play-btn"><i class="fa-solid fa-play"></i></button>
</div>
        
    </div>
</div>
    
    
</div>
<AppLinear/>
<div class="linear-bg"></div>
</template>
<style lang="scss" scoped>
.jumbotron{
    height: 800px;
    background-image:url('../assets/slider82x-scaled.jpg') ;
    background-size: cover;
    color: white;
}

.play-btn{
    padding: 40px 46px;
    border-radius: 100%;
    border: none;
    background-color: white;
    i{
        color: #4154ff;
    }
}
h1{
    font-size: 70px;
}
p{
    color: #98939F;
    margin-bottom: 40px;
}

h4{color: #FF414B;}
button{
    padding: 25px;
    color: white;
    border-radius: 40px;
    background-color: transparent;
    border: 2px solid #98939F;
    margin-right: 30px;
    i{
        color: white;
        font-size: 18px;
    }
}
.channel{
        background-color: #4154FF;
        border: none;
    }
i{
    color: #FFF941;
    font-size: 30px;
    margin: -3px;
}
.shadow{
    background-image:linear-gradient(to right, black 30%,transparent );
height: 800px;
}
</style>
