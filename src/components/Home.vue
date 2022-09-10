<template>
<h1>Input Field</h1>
<input type="text" placeholder="Email" v-model="email" /><br>
<input type="text" placeholder="Password" v-model="password" /><br>
<button v-on:click=getdata()>Get data</button>
</template>

<script>
export default {
    name: 'HomePage',
    data() {
        return{
            email:null,
            password:null
        }

    },
    methods:{
         getdata()
         {
            console.log("email is:"+this.email+" password is:"+this.password)
         }

    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
