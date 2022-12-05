<template>
    <div>名字:{{ userStore.name }}</div>
    <div>年纪:{{ userStore.age }}</div>
</template>
<script lang="ts" setup>
import { useUserStore } from '@/store/user'
const userStore = useUserStore()
</script>
