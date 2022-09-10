<template>
<h1>Two Way Binding</h1>
<input type="text" v-model="data"/>
<h2>{{data}}</h2>
</template>

<script>
export default {
    name: 'HomePage',
    data()
    {
        return{
            data:100
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
