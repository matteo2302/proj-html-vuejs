<script>
export default{}
</script>
<template>
<div class="avada-cont">
    <div class="shadow ">
        <div class="container d-flex flex-column justify-content-center text-center"><h1>"i've failed over and over again in my life. And that is why I succed."</h1>
        <p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
        <p class="color-grey">Arcu auctor nisl, congue sit nisi tincidunt eget proin. In lacinia lactus donec sed massa in ipsum eros, tristique. Gravida suspendisse etiam in iaculis</p>
        <div class="btn-position"><button>Buy avada today ></button></div>
        </div>
        
    </div>
</div>
</template>
<style scoped>
.avada-cont{
    height: 700px;
    background-image: url(../assets/banner2-2x.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}
h1{
    font-size: 45px;
}
.color-grey{
    color: #98939F;
}
.shadow{
    background-image:linear-gradient(to top, black 5%,transparent);
    height: 700px;
}
.container{
    width: 700px;
    height: 700px;
    color:white
}
i{
    color: #FFF941;
    margin: -3px;
    font-size: 25px;
}
button{
    padding: 20px 0;
    width: 200px;
    border-radius: 30px;
    color: white;
    background-color: #4154ff;
    border: none;
}
</style>