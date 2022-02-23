<template>
    <div class="Home">
        <h1>{{ title }}</h1>
    </div>
</template>

<script setup>
/* JS */
import { ref } from 'vue';
const title = ref('Welcome to (vue 3-vite) application')
</script>

<style lang="scss" scoped>
/* SCOPED CSS / SCSS */
.Home {
    height: 100vh;
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #42b883;

    h1 {
        color: #35295e;
        text-transform: uppercase;
        font-weight: 400;
        font-size: 36px;
    }
}
</style>