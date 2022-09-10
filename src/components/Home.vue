<template>
<h1>For-loop</h1>
<ul>
    <li v-for="item in technology" :key="item">
      {{item}}
    </li>
</ul>
</template>

<script>
export default {
    name: 'HomePage',
    data() {
        return {
            technology: [
                "java",
                "python",
                "c",
                "c++",
                "php",
                "node"
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
