<script>
import AppTitle from '../components/AppTitle.vue';

export default {
    components: {
        AppTitle,
    },
    name: 'AppHero',
}

</script>

<template>

    <div class="container">
        <AppTitle></AppTitle>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio recusandae quaerat, voluptas modi distinctio similique soluta assumenda ut maxime eum neque consequatur, aperiam exercitationem itaque laudantium voluptatem explicabo veniam.</p>

        <hr>

        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. .
            
            <button>Learn more</button>
        </p>
        

    </div>

</template>

<style>

.container{
    padding: 15px;
    margin: auto 0;
    
    width: 1000px;
    height: 300px;

    background-color: #E9ECEF;
}

.container p{
    color: black;

    text-align: center;
}

p{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
}

button{
    padding: 10px;

    border-radius: 10px;

    cursor: pointer;

    background-color: #387ADF;
}

</style>