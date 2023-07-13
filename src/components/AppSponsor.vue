<script>
export default {}
</script>
<template>
    <div class="d-flex justify-content-between align-items-center container">
        <div class="cardsponsor d-flex flex-column justify-content-center mx-4 align-items-center text-center">
            <img src="../assets/sponsor-1-2x.png" alt="Yoga Studio" />
            <p class="my-3"><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
            <p>tristique aliquaman in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
            <a class="my-3" href="#">Visit Yoga Studio <i class="fa-solid fa-chevron-right"></i></a>
        </div>
        <div class="cardsponsor d-flex flex-column justify-content-center mx-4 align-items-center text-center">
            <img src="../assets/sponsor-2-2x.png" alt="Fitnes Center" />
            <p class="my-3"><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
            <p>Feugiat etiam dui mauris pharetra mauris sed pharetra. Convallis sapien ornare cras faucibus nulla porta dui
                a.</p>
            <a class="my-3" href="#">Join Fitness Center <i class="fa-solid fa-chevron-right"></i></a>
        </div>
        <div class="cardsponsor d-flex flex-column justify-content-center mx-4 align-items-center text-center">
            <img src="../assets/sponsor-3-2x.png" alt="Fitness Club" />
            <p class="my-3"><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
            <p>Nist at adpiscing, nec, adipiscing commodo aliquam tincidunt. Ligula in habitant imperdient</p>
            <a class="my-3" href="#"> Learn about FC <i class="fa-solid fa-chevron-right"></i></a>
        </div>
        <div class="cardsponsor d-flex flex-column justify-content-center mx-4 align-items-center text-center">
            <img src="../assets/sponsor-4-2x.png" alt="Power gym" />
            <p class="my-3"><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i><i class="fa-solid fa-chevron-up"></i></p>
            <p>Proin in viverra Maecenas et mattis ut nibh enim. Gravida ultricies mi porta lacus. Et posuere velit sed nec
                eleifend</p>
            <a class="my-3" href="#"> Visit Power Gym <i class="fa-solid fa-chevron-right"></i></a>
        </div>

    </div>
</template>
<style lang="scss" scoped>
.cardsponsor {
    margin-top: 50px;
    width: 250px;
    height: 300px;
    img {
        width: 60%;
        height: 60%;
    }
}
p{
    font-size: 16px;
}
i{
    color: #4154ff;
    margin: -3px;
    font-size: 24px;
}
a {
    font-weight: bold;
    color: black;
    i{
        color: black;
        font-size: 14px;
    }
}
.container{
    height: 600px;
}
</style>