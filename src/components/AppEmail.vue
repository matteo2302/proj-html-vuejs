<script>
export default {}
</script>
<template>
    <div class="shadow-bg">
        <div class="email-cont">
            <div class="container">
                <div class="width d-flex flex-column justify-content-center p">
                    <h3>join our mailing list today</h3>
                    <h1>insider offer & flash sales in your inbox evry week.</h1>
                    <p><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i
                            class="fa-solid fa-chevron-up"></i></p>
                    <div class="d-flex align-items-center">
                        <div class="input-group my-5">
                            <input type="text" class="form-control" placeholder="Insert your email ...*"
                                aria-label="Recipient's username" aria-describedby="basic-addon2">

                        </div><button>subscribe</button>
                    </div>

                    <p>curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur
                        adipiscing
                        elit sed porttitors lectus.</p>
                </div>

            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.email-cont {
    background-image: linear-gradient(to right, black 50%, transparent);
    height: 500px;
    color: #98939F;
}

h3 {
    color: #FF414B;
}

h1 {
    color: white;font-size: 40px;
}

i {
    color: #FFF941;
    margin: -2px;
}

.container {
    height: 500px;
}

.form-control {
    width: 300px;
    border-radius: 50px;
}

.input-group {
    margin-right: 50px;
    width: 500px;
}

button {
    border-radius: 50px;
    width: 200px;
    height: 37.6px;
    font-weight: 500;
    color: white;
    background-color: #4154FF;
}

.shadow-bg {
    background-image: url(../assets/banner1-2x.jpg);
    background-size: contain;
    background-repeat: no-repeat;
    background-position: right;
    height: 500px;
}
.width{
    height: 500px;
    width: 700px;
}</style>