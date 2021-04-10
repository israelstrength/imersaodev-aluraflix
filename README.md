# aluraflix imersao.dev

Neste projeto eu aprendi como :

Criar uma primeira array de filmes usando a sintaxe [];
Utilizar o método filmes.push("Nome Do Filme") para inserir um novo elemento na lista (ou seja, um novo filme na array);
Descobrir a quantidade de elementos em uma array com o método array.length;
Selecionar elementos de uma array utilizando a sintaxe array[número], lembrando sempre que o primeiro índice começa com zero, ou seja, array[0] para o primeiro elemento;
Utilizar a instrução for para iterar, ou seja, percorrer todos os elementos de uma array;
Criar uma array com imagens de pôsters de alguns filmes que gostamos;
Montar a lógica do programa que vai iterar esta array de filmes e exibir cada um deles na tela, integrando o for do JavaScript com a tag <img> do HTML.
Desafios dessa aula!

um tipo de lista de elementos, assim como algumas ferramentas para alterarmos e trabalharmos com estas listas. Depois de criarmos uma lista, exibir os pôsters de todos os nossos filmes preferidos na tela do navegador. Durante este projeto, nós tínhamos usado o código abaixo:

function listarFilmesNaTela(filme) {
  var listaFilmes = document.querySelector('#listaFilmes')
  var elementoFilme = "<img src=" + filme + ">"
  listaFilmes.innerHTML = listaFilmes.innerHTML + elementoFilme
}
