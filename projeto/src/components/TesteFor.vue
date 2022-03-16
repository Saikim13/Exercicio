<template>
    <div class="teste-for">
        <h2>Teste for</h2>
        <ul>
            <li v-for="animal of animais" v-bind:key="animal.id">
                <img v-bind:src="animal.url" v-bind:alt="animal.name"/>
            </li>

        </ul>
    </div>
</template>

<script>
export default {
    name: 'TesteFor',
    data() {
        return {
            animais: [
                {
                    id: 1,
                    name: 'Gato',
                    url: 'https://www.petz.com.br/blog/wp-content/uploads/2020/04/meu-primeiro-gato.jpg'
                },
                {
                    id: 2,
                    name: 'Cachorro',
                    url: 'https://image.cachorrogato.com.br/thumb/1200/630/1/imagens/original/imagem858.jpg" alt= "cachorro'
                }
            ]
        }
    }
    
}
</script>

<style scoped>

</style>