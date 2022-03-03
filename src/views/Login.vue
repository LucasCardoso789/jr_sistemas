<template>
    <div class="login">
        <span class="db"><img src="../assets/images/logos/logo-icon.png" alt="logo" /></span>
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
        <p> 
            Esqueceu sua senha?
            <span>
                <router-link to="/esqueceu_senha">Clique aqui</router-link>
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
                this.$router.replace("/admin")
            }
        }
    }
</script>

<style scoped>

</style>