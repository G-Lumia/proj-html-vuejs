<template>
    <div>
        <img :src="'/src/img/shop-images/' +car.img" :alt=car.name>
    </div>
</template>
<script>
export default {
    name: 'CarCard',
    props: ['car'],
    mounted() {
        console.log(this.car.img);
    }
}
</script>
<style lang="scss">
    
</style>