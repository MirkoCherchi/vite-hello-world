<script>
export default {
    name: 'h1',
    data() {
        return {
            title: 'La mia prima app con Vite!',
        }
    }

}
</script>


<template>
    <h1>{{ title }}</h1>
</template>

<style scoped>
h1 {
    color: green;
}
</style>