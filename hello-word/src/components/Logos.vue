<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logo" src="../assets/1.jpeg" alt="Sonic 1">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/2.jpeg" alt="Sonic 2">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/3.jpeg" alt="Sonic 3">
        </div>
    </div>
</template>
    
<script>
export default {
    name : 'Logos'
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto;
    
}

.item-logos {
    width: 150px;
    height: 150px;
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
}

.item-logos .logo{
    width: 150px;
    height: 150px;
}
</style>