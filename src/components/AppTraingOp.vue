<script>
import AppTrainCards from './AppTrainCards.vue';
export default{
    components:{AppTrainCards}
}
</script>
<template>
<div class="training-op-cont d-flex justify-content-center align-items-center">
    <AppTrainCards/>
    
</div>
</template>
<style scooped>
.training-op-cont{
    height: 600px;
    background-color: black;
}
</style>