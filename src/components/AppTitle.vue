<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
};
</script>

<template>
    <h1> {{ title }} </h1>
</template>

<style scoped>
h1 {
    text-align: center;
    margin-top: 10rem;
    text-shadow: 2px 5px 2px rgba(143, 64, 16, 0.54);
}
</style>