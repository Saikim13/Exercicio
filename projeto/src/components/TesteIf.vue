<template>
    <div class="teste-if">
        <h1 v-if="podeVer">Agora Vue</h1>
        <h1 v-else>Agora Num Vue</h1>
    </div>
</template>

<script>
export default {
    name: 'TesteIf',
    data() {
        return {
            podeVer: false
        }
    }
    
}
</script>

<style scoped>

</style>