<template>
    <div>
        <div v-for="item in items" :key="item.id">
            {{ item }}
        </div>
        <input v-model="data" type="text" />
    </div>
</template>

<script>
    export default {
    }
</script>

<style scoped>

</style>