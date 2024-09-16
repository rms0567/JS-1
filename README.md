!DOCTYPE html>

<html lang="pt-BR">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Exercício querySelector</title>

<style>

.destaque (

background-color: yellow;

}

</style>

 </head>

<body>

<h1 class="titulo">Bem-vindo ao exercíciol</h1>

<p class="descricao">Este é um parágrafo para ser modificado.</p>

<button class="mudarTextoBotao">Mudar Texto</button>

<button class="destacarBotao">Destacar Titulo</button>

<script src="script.js"></script>

</body>

 </html>
 document.querySelector('.mudarTextoBotao').addEventListener('click', function() {

const paragrafo document.querySelector('.descricao');

paragrafo.textContent = 'Texto alteradol';

document.querySelector('.mudarTextoBotao').addEventListener('click', function() {

const paragrafo document.querySelector('.descricao');

paragrafo.textContent = 'Texto alteradol';

 });

document.querySelector('.destacarBotao').addEventListener('click', function() {

const titulo document.querySelector('.titulo');

titulo.classList.add('destaque');

 });});



document.querySelector('.destacarBotao').addEventListener('click', function() {

const titulo document.querySelector('.titulo');

titulo.classList.add('destaque');

});
