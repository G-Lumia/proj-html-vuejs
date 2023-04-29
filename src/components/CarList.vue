<template>
    <div>
        <div class="row">
            <CarCard v-for="(car,index) in carsList" :car="car" :key="index"/>
        </div>
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