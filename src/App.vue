<script setup>
import TheHeader from "./components/header/TheHeader.vue";
import TheFooter from "./components/footer/TheFooter.vue";
</script>

<template>
    <div class="flex flex-col min-h-[100vh]">
        
        <div class="">
            <TheHeader/>
        </div>
        
        <div class="flex-1">
            Main
        </div>
        
        <div class="mt-auto">
            <TheFooter/>
        </div>
        
    </div>
</template>

<style lang="scss" scoped>
</style>
