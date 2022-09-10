<template>
<h1>child-compo test</h1>
<h2 v-for="item in users" :key="item"><User :data="item" :getdata="getdata" /></h2>
</template>

<script>
import User from './User.vue';

export default {
    name: "HomePage",
    components: {
        User
    },methods:{
        getdata(x){
            console.log("Congratulation " + x)
        }
    },
    data() {
        return {
            users: [{
                    name: "anil",
                    email: "anil@test.com"
                },
                {
                    name: "sam",
                    email: "sam@test.com"
                },
                {
                    name: "rey",
                    email: "rey@test.com"
                },
                {
                    name: "hey",
                    email: "hey@test.com"
                },
                {
                    name: "pit",
                    email: "pit@test.com"
                }
            ]
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
