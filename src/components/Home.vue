<template>
<h1>Radio and CheckBox</h1>
<label for="java">Java</label>
<input type="checkbox" id="java" value="java" v-model="technology" /><br>
<label for="php">PHP</label>
<input type="checkbox" id="php" value="php" v-model="technology" /><br>
<label for="python">python</label>
<input type="checkbox" id="python" value="python" v-model="technology" /><br>
<h2>{{technology}}</h2>
<br><br>
<h2>Radio Button for profession</h2>
<label for="stu">Student</label>
<input type="radio" id="stu" value="stu" v-model="profession"/><br>
<label for="dev">Developer</label>
<input type="radio" id="dev" value="dev" v-model="profession"/><br>
<h2>profession :{{profession}}</h2>
</template>

<script>
export default {
    name: 'HomePage',
    data() {
        return {
            technology: [],
            profession:[]
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>
