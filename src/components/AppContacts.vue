<script>
export default{
}
</script>
<template>
<div class="contacts-cont ">
    <div class="d-flex container align-items-center justify-content-between">
        <div class="contax-box text-center">
    <img src="../assets/logo.png" alt="logo">
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, sed dolor. Optio sint veniam consequatur voluptatem sapiente facere eos consequuntur, eaque quasi minus quia dicta cupiditate, recusandae quis a id!</p>
    <div class="d-flex justify-content-center"><i class="fa-brands fa-facebook"></i><i class="fa-brands fa-twitter"></i><i class="fa-brands fa-youtube"></i><i class="fa-brands fa-instagram"></i><i class="fa-brands fa-linkedin-in"></i></div>
</div>
<div class="contax-box text-center">
    <h3>RECENT POSTS</h3>
<ul>
    <li><a href="#">> The best protein shake</a></li>
    <li><a href="#">> Ultimate arm workout</a></li>
    <li><a href="#">> New gears avaible now</a></li>
    <li><a href="#">> Tips to find training parteners</a></li>
    <li><a href="#">> 20 best healthy recipes</a></li>
</ul>
</div>
<div class="contax-box text-center">
    <h3>CONTACT INFORMATION</h3>
<ul>
    <li class="addres">4746 Tipple Road Michigan 48449</li>
    <li>Mobile:1.800.000.0000</li>
    <li>Email: info@your-company.com</li>
</ul>
</div></div>
    
</div>

</template>
<style lang="scss" scoped>
i{
    color: #FF414B;
    margin: 0 5px;
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
        height: 30px;
    }
}
.addres{
    color: transparent 0.7;
}
li{
    padding: 10px 0;
}

</style>