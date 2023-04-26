<template>
    <header class="py-4 d-flex justify-content-center">
        <div class="container d-flex align-items-center  justify-content-between m-0">
            <img src="../assets/img/logo/logo-autocar11.png" alt="logo">
            <div class="links px-4 d-flex gap-4">
                <a href="#"> Home </a>
                <a href="#"> About Us </a>
                <a href="#"> Vehicles </a>
                <a href="#"> Dealers </a>
                <a href="#"> Packages </a>
                <a href="#"> Blog </a>
                <a href="#"> Contact </a>
            </div>
            <div class="blackLink">
                <img src="../assets/img/header/padlock.png" alt="account">
                <a href="#"> My Account</a>
            </div>
            <div class="blackLink">
                <img src="../assets/img/header/add.png" alt="add">
                <a href="#"> Add Car </a>
            </div>
            <div class="blackLink">
                <img src="../assets/img/header/headphones.png" alt="headphones">
                <a href="#"> +1 (234) 567 89 10</a>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name : 'HeaderApp'
}
</script>

<style lang="scss" scoped>
    header{
        height:80px;
        width:100%;
    }

    header img{
        max-width:80px;
    }

    a{
        text-decoration: none;
        font-size: 0.7rem;
    }

    .links a{
        color: #000000;
        &:hover{
            color: #AAAAAA;
            transition: 0.5s;
        }
    }

    .blackLink{
        background-color: #000000;
        margin: 5px 10px 5px 10px;
        padding: 3px 6px 3px 6px;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5px;
        height:100%;
    }
    .blackLink a{
        color: #ffffff;
        &:hover{
            color: #AAAAAA;
            transition: 0.5s;
        }
    }
    .blackLink img{
        max-height: 100%;
        filter: invert(1);
    }
</style>