<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld msg="Welcom to Vue.Js" />
<Home msg="hello Lakshmi Narayana"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue';

export default {
    name: 'App',
    components: {
    HelloWorld,
    Home
}
}
</script>


