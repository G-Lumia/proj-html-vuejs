<template>
    <main>
        <MainCarousel/>
        <CarList/>
    </main>
</template>

<script>
import MainCarousel from './MainCarousel.vue';
import CarList from './CarList.vue';
export default {
    name : 'MainApp',
    components : {
        MainCarousel,
        CarList
    }
}
</script>
<style lang="scss">
    
</style>