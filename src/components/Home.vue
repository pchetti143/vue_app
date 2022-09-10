<template>
<h1 v-on:mousemove=mousemove()>Home Component {{msg}}</h1>
<button v-on:click=getdata()>Click me</button>
<h1>{{count}}</h1>
</template>

<script>
export default {
    name: 'HomePage',
    props: {
        msg: String
    },
    data() {
           return{ count:0}
    },
    methods: {
        getdata() {
            alert("Button clicked")
            this.count+=1
        },
        mousemove() {
            console.log("event fired")
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
