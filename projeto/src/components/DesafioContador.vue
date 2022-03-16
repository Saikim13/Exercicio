<template>
    <div class="desafio-contador">
        <h2>Contador: {{ contador }}</h2>
        <span>
            <button @click="somar">+</button>
             <button @click="subtrair">-</button>

        </span>
    </div>
</template>

<script>
export default {
    name: 'DesafioContador',
    data(){
        return {
            contador: 0
        }
    },
    methods: {
        somar() {
            this.contador++;
        },
        subtrair() {
            this.contador--;
        }
    }


}
</script>

<style scoped>

</style>