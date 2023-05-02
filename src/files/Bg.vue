<script setup>
import Card from "./Card.vue"
import GiriGiriAi from "./GiriGiriAi.vue"
import SomeThing from "./Something.vue"
</script>

<template>
    <div class="area">
        <div class="zone1">
            <Card />
            <Card />
            <Card />
        </div>
        <div class="zone2">
            <GiriGiriAi />
        </div>
        <div class="zone1">
            <Card />
            <Card />
            <Card />

        </div>
        <div class="zone2">
            <GiriGiriAi />
        </div>
        <div class="zone3">
            <SomeThing />

        </div>
       
    </div>
</template>

<style scoped>
.zone1{
    padding: 10px;
    display: flex;
    justify-content: space-around;
    
}
.zone3{
    align-items: center;
    padding: 14px;
    height: 200px;
}
.area{
    background-color: bisque;
    flex-grow: 1;
}
</style>