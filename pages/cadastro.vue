
<template>
<div class="container-principal, fade-in">
    <div class="container-titulo">
        <header>
        <h2>CADASTRO</h2>
        </header>
    </div>
    <div class="container-form">
        <form action="">

                <label for="">Nome</label>
                <input type="text"
                name="" id=""
                placeholder="Digite seu nome"
                required>
       
                <label for="">Data de nascimento</label>
                <input type="date"
                name="" id=""
                placeholder="Digite sua data de nascimento"
                required>

                <label for="">CPF</label>
                <input type="text"
                name="" id=""
                placeholder="Digite seu CPF"
                required>

                <label for="">E-mail</label>
                <input type="email"
                name="" id=""
                placeholder="Digite seu e-mail"
                required>

                <label for="">Senha</label>
                <input type="password"
                name="" id=""
                placeholder="Digite sua senha"
                required>
           
           
            <div class="button-container">
                <button type="submit" class="button-enviar">Cadastrar</button>
            </div>
        </form>
        <p class="paragrafo">Já possui uma conta? </p>
        <p class="cadastrar"><nuxt-link to="/login" class="linkheader">Faça seu Login</nuxt-link></p>
    </div>
</div>
</template>

<style scoped>
@import '/components/assets/sylelogin.css';
</style>

<script setup lang="ts">
definePageMeta({
  layout: 'layoutlogin'
})
</script>
