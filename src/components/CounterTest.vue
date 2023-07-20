<template>
    <h1>
        Hola desde el componente Counter
    </h1>
    <button @click="disminuir()">-</button>
    <br>
    {{ contador }}
    <br>
    <button @click="aumentar()">+</button>
</template>

<script>
export default {
    data() {
        return {
            contador: 0,
        }
    },
    methods: {
        aumentar() {
            this.contador++
        },
        disminuir() {
            this.contador--
        }
    },
}
</script>
<style scoped>
h1 {
    color: red;
}
</style>