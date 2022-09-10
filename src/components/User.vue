<template>
    <h6>Name is : {{data.name}} <br> My email is : {{data.email}}</h6>
    <button v-on:click="getdata(data.name)">Click me </button>
</template>
<script>
     export default{
        name:"User-Page",
        props:{
            data:Object,
            getdata:Function
        }
     }
</script>