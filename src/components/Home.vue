<template>
<h1>Home Component</h1>
<h2>{{email}}+{{msg}}+hai+{{getName("praneeth")}}+{{data().email}}</h2>
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

        }
    },
    methods: {
        getName(x) {
            return "hello" + x;
        },
        data() {
            return {
                email: "hey@test.com",
                mobile: "998844"
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
