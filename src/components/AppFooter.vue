<script>
import AppCopyright from './AppCopyright.vue';
import AppContactsVue from './AppContacts.vue'
import AppWorkoutTodayVue from './AppWorkoutToday.vue';
import AppSponsor from './AppSponsor.vue';
export default{
    components:{
        AppSponsor,
        AppWorkoutTodayVue,
        AppContactsVue,
        AppCopyright

    }
}
</script>
<template>
<AppSponsor/>
<AppWorkoutTodayVue/>
<AppContactsVue/>
<AppCopyright/>
</template>
<style scoped>
</style>