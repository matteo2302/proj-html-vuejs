<script>
export default{}
</script>
<template>
    <nav > 
        <div class=" container d-flex align-items-center justify-content-between nav-cont">
        <img src="../assets/logo.png" alt="logo">
        <ul class="d-flex">
            <li class="color-w">home</li>
            <li>service</li>
            <li>about</li>
            <li>videos</li>
            <li>blog</li>
            <li>store <span>new</span></li>
            <li><button>Schedule a workout</button></li>
            <li><i class="fa-solid fa-cart-shopping"></i></li>
            <li><i class="fa-solid fa-magnifying-glass"></i></li>
        </ul>
    </div>
        

    </nav>
</template>
<style lang="scss" scoped>
nav{
        background-color: black;
}
.nav-cont{
    height: 80px;
    color: #98939F;
    img{
        height: 40px;
    }
}
li{
    margin-left: 50px;
    display: flex;
    align-items: center;
    span{
        margin-left: 3px;
        border-radius: 5px;
        padding: 0 4px;
        background-color: #FFF941;
        color: black;
    }
}
.color-w{
    color: white;
}
button{
    padding: 15px 0;
    width: 150px;
    border-radius: 30px;
    color: white;
    background-color: #4154ff;
    border: none;
}
</style>