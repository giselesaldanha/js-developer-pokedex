## PROMPT PARA CRIAÇÃO DA IMAGEM DE CAPA PROJETO DA POKEDEX
# Ferramenta utilizada: ChatGPT (versão gratuita)
Crie uma imagem de uma pokedex em um design clássico com um fundo futurista.
Formato da Imagem: Retangular

## PROMPT PARA CRIAÇÃO DO README DO PROJETO DA POKEDEX
# Ferramenta utilizada: ChatGPT (versão gratuita)
Criar um readme.md do projeto Pokedex.
A primeira seção do arquivo deve deixar claro que a criação desde arquivo readme foi realizado com a ajuda de IA Generativa (chat GPT – versão gratuita) durante o Bootcamp “Microsoft IA for Tech” em parceira com a DIO. A palavra DIO deve ser um hiperlynk para o site https://web.dio.me/home.
Objetivo do Projeto: Criar uma pokedex utilizando JavScript e CSS
No topo do arquivo deve ser colocada de maneira centralizada a Imagem de Capa do projeto: ./assets/Pokedex.jpg
Ao final do Arquivo criar uma seção de agradecimento agradecendo a Microsoft e a DIO pela oportunidade de realizar esse Bootcamp e melhorar meu conhecimento sobre Inteligência Artificial.
Para a criação do README com seus pré-requisitos e descrição considere o index.html a seguir
***
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokedex</title>

    <!-- Normalize CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
        integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHpc5Jtzgvbuzx5VozKpWvQ+4nXhPdFgmx8xqexRcpAglTj9sIBWINXa8x5w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- Font Roboto -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;500;700&display=swap" rel="stylesheet">

    <!-- Nosso CSS -->
    <link rel="stylesheet" href="/assets/css/global.css">
    <link rel="stylesheet" href="/assets/css/pokedex.css">
</head>

<body>
    <section class="content">
        <h1>Pokedex</h1>

        <ol id="pokemonList" class="pokemons">
            <!-- ..... Pokemons here ..... -->
        </ol>

        <div class="pagination">
            <button id="loadMoreButton" type="button">
                Load More
            </button>
        </div>
    </section>

    <!-- Nosso JS -->
    <script src="/assets/js/pokemon-model.js"></script>
    <script src="/assets/js/poke-api.js"></script>
    <script src="/assets/js/main.js"></script>
</body>

</html>
***
