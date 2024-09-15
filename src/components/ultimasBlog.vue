<script setup>
</script>

<template>
  <div class="blog-section">
        <h2>Últimas do blog</h2>
        <div class="post">
            <a href="https://fastcompanybrasil.com/tech/inteligencia-artificial/esqueca-a-interface-estatica-vem-ai-a-interface-em-tempo-real-gerada-por-ia/?utm_source=the_news&utm_medium=newsletter&utm_campaign=13-09-2024&_bhlid=09eebaabb6b68b31c0f872687d1b7b9e5b655eb9">Interface em tempo real por IA</a>
            <p>O futuro são as interfaces generativas, que mudam com base nas interações e preferências dos usuários</p>
        </div>
        <div class="post">
            <a href="https://thenews.waffle.com.br/mundo/a-primeira-caminhada-de-um-homem-comum-no-espaco?utm_source=the_news&utm_medium=newsletter&utm_campaign=13-09-2024&_bhlid=e667b5b4d3b9dc51ddaad7e2b341b48fd192fed4">A primeira caminhada de um homem “comum” no espaço</a>
            <p>A SpaceX elevou mais uma vez os patamares da aviação espacial, realizando a primeira caminhada no espaço comercial na sua missão Polaris Dawn.</p>
        </div>
        <div class="post">
            <a href="https://thenews.waffle.com.br/tecnologia/mcdonalds-caminha-para-ter-menos-atendentes-humanos">McDonald’s caminha para ter menos atendentes humanos</a>
            <p>O McDonald’s está lançando novos quiosques digitais nos EUA que podem receber dinheiro e dar o troco</p>
        </div>
        <a href="#" class="view-all">Ver tudo</a>
    </div>
</template>

<style scoped>
      * {
            font-family: Arial, sans-serif;
        }

        .blog-section {
            width: 600px;
            margin: 50px auto;
        }

        h2 {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #58290c;
        }

        .post {
            margin-bottom: 20px;
        }

        .post a {
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            color: #BF6122;
        }

        .post a:hover {
            text-decoration: underline;
        }

        .post p {
            margin: 5px 0;
            color: #666;
        }

        .view-all {
            display: inline-block;
            margin-top: 20px;
            font-size: 16px;
            color: #be9729;
            text-decoration: none;
        }

        .view-all:hover {
            text-decoration: underline;
        }
</style>
