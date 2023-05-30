<script setup lang="ts"></script>

<template>
    <div>
        <a href="https://vitejs.dev" target="_blank">
            <img src="/vite.svg" alt="Vite logo" name="1" age="2" />
        </a>
        <a href="https://vuejs.org/" target="_blank" name="1" age="2">
            <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
        </a>
    </div>
    <div>test123</div>
    <span>123</span>
</template>

<style scoped>
    .logo {
        height: 6em;
        padding: 1.5em;
        will-change: filter;
        transition: filter 300ms;
    }
    .logo:hover {
        filter: drop-shadow(0 0 2em #646cffaa);
    }
    .logo.vue:hover {
        filter: drop-shadow(0 0 2em #42b883aa);
    }
</style>
