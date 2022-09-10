<template>
    <h1>Child Component</h1>
    <p>my name is {{fname}} and i have {{cardata}}</p>
</template>
<script>
    export default{
        name:"ChildPage",
        props:{
            fname:String,
            cardata:Object
        }
    }
</script>