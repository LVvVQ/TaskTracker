<template>
    <footer>
        <p>Copyright &copy; 2021</p>
        <router-link to="/about">About</router-link>
    </footer>
</template>

<script>
import router from '../router'

export default {
    name: 'About',
    components: {
        router,
    }
}
</script>

<style scoped>
a {
    color: #333;
}

footer {
    margin-top: 30px;
    text-align: center;
}
</style>
