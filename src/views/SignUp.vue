<template>
    <div class="sign-up">
        <h1>Crie uma nova conta</h1>
            <input type="text" placeholder="Email">
        <br>
            <input type="password" placeholder="Senha">
        <br>
        <button>Registrar</button>
        <br>
        <span>
            ou retorno para o 
            <router-link to="login">Login</router-link>
        </span>
    </div>
</template>