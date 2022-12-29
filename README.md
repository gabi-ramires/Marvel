# Marvel 
Projeto desenvolvido para consumir a API da Marvel para obter dados de 3 personagens: nome, ID, imagem e 5 histórias em que esses personagens aparecem.
A documentação da API pode ser encontrada nesse link: https://developer.marvel.com/docs

## Tecnologias
PHP, HTML, CSS, PHPUnit

## Requisitos
Para o desenvolvimento desse projeto é necessário possuir algum servidor web como por exemplo o Apache e para realizar os testes o PHPUnit. 
Para instalar o PHPUnit pode ser feito de duas formas:
1) Pelo VSCode, basta procurar por "PHPUnit"
2) Pelo Composer: https://getcomposer.org/download
    - Após a instalação do composer, abrir terminal dentro da raiz do projeto
    - Dar o comando: composer require --dev phpunit/phpunit

## Como executar
Basta fazer o download do projeto em zip e descompactar em sua máquina e utilizar algum editor de código de sua preferência.

## Observações
Para fazer as requisições da API, foi necessário gerar um hash do tipo md5, utilizando as chaves pública e privada que a API fornace ao se cadastrar na plataforma e também utilizando um timestamp.
Para maiores detalhes: https://developer.marvel.com/documentation/authorization


Para visualizar o projeto: https://gabrielaramires.com.br/marvel/



