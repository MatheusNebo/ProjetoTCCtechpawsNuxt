<template>
    <div class="fade-in">
    <header>
        <h2>Pets Disponíveis para Adoção</h2>
    </header>
    <section>
    <ul class="pAdocoes">
        <li class="div2">
            <div>
            Nome: Fido <br>
            Idade: 2 anos <br>
            Descrição: Um cão amigável e cheio de energia, adora brincar e é ótimo com crianças.
            </div>
            <div class="button-container">
                <button><nuxt-link to="/infoanimal">Ver Mais</nuxt-link></button>
            </div>
        </li>
        <li>
            Nome: Bella <br>
            Idade: 3 anos <br>
            Descrição: Uma gata carinhosa que adora um bom colo e é muito tranquila.
        </li>
        <li>
            Nome: Max <br>
            Idade: 1 ano <br>
            Descrição: Um cachorro jovem e ativo que precisa de um lar com espaço para correr e brincar.
        </li>
    </ul>
</section>
    </div>
</template>

<style scoped>
@import '/components/assets/sylelogin.css';
</style>
