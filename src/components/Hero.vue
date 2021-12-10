<template>
    <div class="hero">
        <Title/>
    </div>
</template>

<script>
import Title from "./Title.vue";

export default {
    name: 'Hero',
    components: {
        Title
    }
}
</script>

<style scoped>
    .hero {
        width: 100%;
        height: 100vh;
        position: relative;
        background-image: url(../assets/581998-5K-Highway.jpg);
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
    }
</style>