<script setup>
import { ref } from "vue"
import bcrypt from "bcrypt"

const username = ref("")
const password = ref("")
</script>

<template>

    <head>
        <title>Login</title>
    </head>
    <div>
        <input type="text" id="username" placeholder="Username" v-model="username">
    </div>
    <div>
        <input type="password" id="password" placeholder="Password" v-model="password">
    </div>
</template>

<style scoped>
#username #password {
    margin-top: 10px;
    margin-left: 10px;
}
</style>