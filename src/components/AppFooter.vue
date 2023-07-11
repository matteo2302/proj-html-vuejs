<script>
import AppContactsVue from './AppContacts.vue'
import AppWorkoutTodayVue from './AppWorkoutToday.vue';
import AppSponsor from './AppSponsor.vue';
export default{
    components:{
        AppSponsor,
        AppWorkoutTodayVue,
        AppContactsVue

    }
}
</script>
<template>
<AppSponsor/>
<AppWorkoutTodayVue/>
<AppContactsVue/>
</template>
<style scoped>
</style>