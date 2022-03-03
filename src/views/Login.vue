<template>
    <div class="login">
        <h1>Login</h1>
            <input type="text" placeholder="Email">
        <br>
            <input type="password" placeholder="Senha">
        <br>
        <div class="btn-login">
            <button @click="login">Login</button>
        </div>
        <p> 
            Você não tem uma conta?
            <span>
                <router-link to="/registrar">Crie uma conta</router-link>
            </span>
        </p>
    </div>
</template>

<script>
    export default{
        name: 'login',
        data(){
            return {};
        },
        methods: { 
            login: function() {
                this.$router.replace("/")
            }
        }
    }
</script>

<style scoped>

</style>