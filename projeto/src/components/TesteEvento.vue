<template>
    <div class="teste-evento">
        <h1 v-on:click="deixarMaiuscula"> {{ mensagem }} </h1>
    </div>
</template>

<script>
export default {
    name: 'TesteEvento',
    data() {
        return {
            mensagem: 'O rato roeu a roupa do rei de roma'
        }
    },
    methods: {
        deixarMaiuscula() {
            this.mensagem = this.mensagem.toUpperCase();
        }
    }
}
</script>

<style scoped>

</style>