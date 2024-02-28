<script>

export default {
    name: 'AppTitle',
}

</script>

<template>
    
    <div class="container">

        <h1>La mia prima app con Vite!</h1>

        <img src="https://www.filepicker.io/api/file/PrjQ7ZxTQye3aR2Tzt3N" alt="">

    </div>

</template>

<style>

.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
}

h1{
    font-weight: bold;

    text-align: center;
    
    color: #EE4266;
}

.container img{
    width: 150px;
}

</style>