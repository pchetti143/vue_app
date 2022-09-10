<template>
<h1>child-compo test</h1>
<Child :fname="name" :cardata="cars"/>
</template>

<script>
import Child from './Child.vue';

export default {
    name: "HomePage",
    components: { Child },
    data(){
         return{
            name:"chetti",
            cars:{1:"audi",2:"BMW",3:"Benz"}
         }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
