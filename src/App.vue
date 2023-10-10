<script setup>
import ChildCom from './components/ChildCom.vue';
const message = "我是最上層組件";
</script>

<template>
<h1>{{ message }}</h1>
<div class="child">
    <h3>子組件區塊</h3>
    <ChildCom></ChildCom>
</div>

</template>

<style scoped>
.child{
    border: 1cap;
}
</style>