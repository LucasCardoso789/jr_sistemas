<template>
    <div>
        <h1>Pagina administrativa</h1>

        <button @click="login">Voltar</button>
    </div>
</template>


<script>
    export default{
    methods: {
        login() {
                this.$router.replace("/")
            }
    }
}
</script>