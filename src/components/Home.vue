<template>
<h1>Home Component</h1>
<h2>{{email}}+{{msg}}+hai+{{getName("anil")}}</h2>
</template>

<script>
export default {
    name: 'HomePage',
    props: {
        msg: String
    },
    data() {
        return {
            email: "pchetti@opentext.com",
            password: "helloworld",
            getName(x){
                return "chetti"+x;
            }
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
