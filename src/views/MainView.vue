<template>
<div class="container">
    <Sidebar></Sidebar>
    <div class="contet">
        <router-view></router-view>
    </div>
</div>
</template>

<script setup>
import Sidebar from '../components/Sidebar.vue';
</script>

<style>
.container{
    display: flex;
}
.contet{
    flex: 1;
    padding: 20px;
}
</style>