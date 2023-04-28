<template>
    <div>
        <CarCard v-for="(car,index) in carsList" :car="car" :key="index"/>
    </div>
</template>
<script>
import store from '../js/store.js'
import CarCard from './CarCard.vue';
export default {
    name: 'CarList',
    components : {
        CarCard
    },
    data() {
        return {
            carsList : store.carsList
        }
    }
}
</script>
<style lang="scss">
    
</style>