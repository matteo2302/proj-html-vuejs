<script>
import AppLatestCont from './AppLatestCont.vue';
import AppTraingOpVue from './AppTraingOp.vue';
import AppEmail from './AppEmail.vue';
import AppChannel from './AppChannel.vue';
export default{
    data(){
        return{
            channeltitle:'Featured playlist',
            channellink:'View all video',
            channel:[
            {img:'video2-2x',
            title:'Thighs & glute workout',
            link:'Increase your mobility',
           },
            {img:'video7-2x',
            title:'Lift, firm & perk up',
            link:'Feel young again',
            },
            {img:'video9-2x',
            title:'Slim & trim you waist',
            link:'Shed those extra pounds',
            }
        ]
        }
        
    },
    components:{AppChannel,AppEmail,AppTraingOpVue,AppLatestCont}
}</script>
<template> 
<AppChannel :channeltitle="channeltitle" :channellink="channellink" :channel="channel"/>
<AppEmail/>
<AppTraingOpVue/>
<AppLatestCont/>
</template>
<style scoped></style>
