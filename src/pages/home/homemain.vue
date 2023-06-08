<template>
    <headerCom></headerCom>
    <div class="container" id="container">
        <router-view></router-view>
    </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import headerCom from '../../components/headerCom.vue';

</script>

<style lang='scss' scoped>
.container {
    width: 100vw;
    min-height: 100vh;
    padding: 4px 16px;
    background-color: #f4f5f9;
}
</style>
