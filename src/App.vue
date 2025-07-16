<script setup>
import { RouterLink, RouterView } from "vue-router";


</script>

<template>
    <h1>DEV HUB FRONTEND</h1>
    <p>
        <b>Current route:</b> {{ $route.fullPath }}
    </p>
    <nav>
        <RouterLink to="/">Go to Home</RouterLink>
        <RouterLink to="/login" class="inlinelink">Go to Login</RouterLink>
        <RouterLink to="/register" class="inlinelink">Go to Register</RouterLink>
    </nav>
    <main>
        <RouterView />
    </main>
</template>

<style scoped>
.inlinelink {
    margin-left: 10px;
}
</style>
