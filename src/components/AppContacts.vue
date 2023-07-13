<script>
export default{
}
</script>
<template>
<div class="contacts-cont ">
    <div class="d-flex container align-items-center justify-content-between">
        <div class="contax-box text-center">
    <img src="../assets/logo.png" alt="logo">
    <p class="my-5">Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices muaììauris.</p>
    <div class="d-flex justify-content-center"><i class="fa-brands fa-facebook"></i><i class="fa-brands fa-twitter"></i><i class="fa-brands fa-youtube"></i><i class="fa-brands fa-instagram"></i><i class="fa-brands fa-linkedin-in"></i></div>
</div>
<div class="contax-box text-center">
    <h5>RECENT POSTS</h5>
<ul>
    <li><a href="#"><i class="fa-solid fa-chevron-right"></i> The best protein shake</a></li>
    <li><a href="#"><i class="fa-solid fa-chevron-right"></i> Ultimate arm workout</a></li>
    <li><a href="#"><i class="fa-solid fa-chevron-right"></i> New gears avaible now</a></li>
    <li><a href="#"><i class="fa-solid fa-chevron-right"></i> Tips to find training parteners</a></li>
    <li><a href="#"><i class="fa-solid fa-chevron-right"></i> 20 best healthy recipes</a></li>
</ul>
</div>
<div class="contax-box text-center">
    <h5>CONTACT INFORMATION</h5>
<ul>
    <li class="addres">4746 Tipple Road Michigan 48449</li>
    <li class="number">Mobile:1.800.000.0000</li>
    <li class="email">Email: info@your-company.com</li>
</ul>
</div></div>
    
</div>

</template>
<style lang="scss" scoped>
i{
    color: #FF414B;
    margin: 0 8px;
    font-size: 18px;
}
.contacts-cont{
    height: 600px;
    background-color: black;
    color: white;
} 
.container{
    height: 600px;
}
.contax-box{
    width: 300px;
    height: 300px;
    img{
        width: 70%;
        height: 40px;
    }
}
.addres{
    color: #98939F;
    margin: 0 20px;
}
li{
    padding: 10px 0;
    i{
        color: white;
    }
}
ul{
    padding-left: 0;
}
.number,.email{
    padding: 0;
}
</style>