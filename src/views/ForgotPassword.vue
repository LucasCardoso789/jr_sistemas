<template>
    <div class="forgot-password">
        <h1>Esqueceu a senha</h1>
        <span>Digite seu email:</span>
            <input type="text" placeholder="Email">
        <br>
        <button @click="recuperar">Enviar</button>
        <br>
        <span>
            Ou retorne para o 
            <router-link to="login">Login</router-link>
        </span>
    </div>
</template>

<script>
    export default{
        methods: {
            recuperar() {
                alert("Foi enviado para o seu email um link para redefinir sua senha!")
                this.$router.replace("/login")
            }
        }
    }
</script>