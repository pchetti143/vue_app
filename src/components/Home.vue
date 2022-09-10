<template>
<h1>Radio and CheckBox</h1>
<h4 v-if="show">Condition true</h4>
<h4 v-else>Condition False</h4>
<button v-on:click="show=!show">Click me</button>
</template>

<script>
export default {
    name: 'HomePage',
    data(){
        return {show:true}
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
