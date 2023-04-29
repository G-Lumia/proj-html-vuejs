<template>
    <div class="card col-4">
        <img class="car-img" :src="'/src/img/shop-images/' + car.img" :alt=car.name>
        <div class="card-body">
            <h3 class="card-title">{{car.name}}</h3>
            <p class="card-text"> {{ car.category }}</p>
            <div class="gap-3 d-md-flex d-none">
                <div class="d-flex align-items-center details">
                    <img src="../img/svg/dollar-symbol-svgrepo-com.svg" alt="dollar">
                    <p>
                        {{car.price}}
                    </p>
                </div>
                <div class="d-flex align-items-center details">
                    <img src="../img/svg/car-svgrepo-com.svg" alt="dollar">
                    <p>
                        {{car.brand}}
                    </p>
                </div>
                <div class="d-flex align-items-center details">
                    <img src="../img/svg/fuel-svgrepo-com.svg" alt="dollar">
                    <p>
                        {{car.fuel}}
                    </p>
                </div>
            </div>
        </div>
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
    p{
        font-weight:100;
        font-size: 12px;
    }
    
    .details{
        height:30px;
    }

    .car-img{
        width:100%;
    }

    .card{
        width:200px;
    }
</style>