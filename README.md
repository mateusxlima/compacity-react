# Compacity

## Descrição

Projeto criado por Mateus Lima, para um desafio na empresa CompassoUOL, Chapecó - SC 

Projeto construido usando React JS, bootstrapped com `create-react-app`, para rodar o projeto basta dar o comando `npm start` e acessar o endereço http://localhost:3000 no navegador.

## API

Em conjunto com este projeto foi desenvolvida uma API em Spring boot, ela foi desenvolvida pelo meu colega Rafael, e você pode ter acesso ao repositório dele no GitHub em: 

* **Rafael** - [rafamp1991](https://github.com/rafamp1991/DesafioBackend)

Para conectar a uma API externa basta alterar o endereço para o link da API em questão.

## Arquitetura e componentização

A arquitetura do projeto é baseada na componentização, que é o pilar principal do React, em essência temos dois componentes principais, um para a tela do cliente e outro para a tela das cidades, e cada um destes se subdivide em subcomponentes, sendo que cada uma das telas se subdivide em outros três componentes menores, duas tabelas e um formulário, o formulário serve para cadastrar novos registros, já as tabelas tem objetivos distintos, enquanto uma renderiza os dados da pesquisa de um dado especifico, a outra renderiza todos os registros do banco de dados.
Ainda temos outros componentes como Header, Footer e ApiService que serve para fazer as chamadas à API, e também o PopUp que da alertas visuais.

## Pré requisitos

* Nodejs Apartir da versão 12.16.1

## Como compilar

Antes de compilar é necessario executar o comando `npm install` que se responsabiliza por instalar as dependências necessárias automaticamente, logo após basta executar o comando `npm start`.

#### Caso as depêndencias não sejam instaladas de forma automatica você pode instalá-las manualmente usando o NPM.

###### Dependências a serem instaladas:

* React
* Create-react-app
* Materialize-css
* React-router-dom

## Licença

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)