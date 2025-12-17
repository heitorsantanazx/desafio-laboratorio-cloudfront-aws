# Desafio de Laboratório CloudFront e S3

<p>
    Criei este repositório com objetivo de documentar o que fiz no laboratório e minha aventura no html, onde fiz comandos bem básicos para criar uma página. Com este desafio eu consegui:
</p>

- Criei um arquivo html e css, na qual seria a página de minha cadela
- Coloquei esses arquivos em meu bucket
- Para ficar mais rápido e pelo cache eu usei o cloudfront

<p text-align="justify">
O objetivo é que o usuário iria acessar esta aplicação e o cloudfront iria verificar se o que o usuário deseja encontrar está cache, caso sim ele iria trazer minha aplicação web para ele e caso não ele iria pegar na origem, para na próxima vez ele pegar em cache. Por fim antes de finalizar o desafio, eu segui boas práticas em questão de desabilitar a minha distribuição no CloudFront e depois apaguei o meu bucket, mesmo esse laboratório sendo num sandbox.
</p>

----

## 1. Primeira parte criei o meu bucket

<img src="./assets/Parte 01.png">

## 2. Segunda parte upei os meus arquivos

<img src="./assets/Parte 02.png">

## 3. Terceira parte criei minha distribuição no CloudFront

<img src="./assets/Parte 03.png">

## 4. Parte final site no ar

<img src="./assets/Parte 04.png">

----

Agradecimentos a Escola da Nuvem por me proporcionar essa oportunidade de me aventurar nos estudos da AWS, ao meu professor Raphael Bernado Ohlsen e por fim meu companheiro de turma Edmar Freitas que me ajudou na parte de configuração da distribuição no CloudFront.