# Desafio {nome} - Python Developer

## Instruções
* Crie um board público no [Trello](https://trello.com/) e organize as tarefas necessárias para finalizar o desafio.
* Envie o link do [Trello](https://trello.com/) e a estimativa de conclusão para **{email}** com o assunto ```teste```
* Utilize Python :snake: para construir o desafio. Fique à vontade para escolher os frameworks, libs, banco de dados, etc.
* Versione o código em um repositório público aqui no Github.
* Envie o link do repositório para **{email}** com o assunto ```Python Developer - {SEU_NOME}```. :trophy:
* Seu desafio será avaliado pelo nosso time de especialistas. Caso seja aprovado, agendaremos uma data para você apresentá-lo.

## Contexto

Boa parte dos pequenos varejistas não utilizam qualquer software para fazer a gestão do próprio catálogo de produtos. Isto acaba gerando uma enorme desorganização operacional e a consequência disso pode ser o fechamento da empresa. 

A necessidade é utilizar um software que permita cadastrar, atualizar, deletar e listar os produtos.

## Sua missão, caso deseje aceitá-la é:

Criar uma API para gestão de produtos. 

#### Product

Campo   | Tipo
--------- | ------
id | id
name | str (128)
description | str (1024)
images | str[]
price | int 
quantity | int
status | enum
created_at | datetime
updated_at | datetime
deleted_at | datetime

#### Email

Campo   | Tipo
--------- | ------
id | id
from | str (64)
to | str (64)
body | str 

## O que você não pode esquecer

* Criar teste unitários
* Validar requisições
* Registrar log de erros (console, arquivo, etc)
* Persistir informações em um banco de dados
* Criar README com as instruções sobre como executar e testar o projeto
* Criar collection no Postman com todas as requisições disponíveis

## O que será um diferencial

* Criar documentação (Swagger, ReDoc, etc)
* Registrar log de requisições e respostas (console, arquivo, etc)
* Disponibilizar endpoint para healthcheck
* Criar Dockerfile

## O que você deve saber responder

* A API está funcionando?
* Ocorreu algum erro recentemente?
* Como eu identifico qual foi o erro?
* Qual é o tempo médio de respota?
* Qual foi o RPM na última hora?

## O que será avaliado

#### Como você planejou

* Organização das tarefas - 
* Tamanho das tarefas -
* Estimativa - 
* Esforço -
* Categorização das tarefas (codificação, teste, etc)

#### Como você desenvolveu

* Simplicidade e testabilidade do código - ```O código deve ser fácil de entender e testar```
* Duplicação de código - ```Reaproveite o máximo de código para evitar duplicações```
* Vulnerabilidades - ```Evite deixar informações sensíveis no código (senhas, conn strings, etc)```
* Cobertura de testes - ```Tente superar 70% de cobertura```
* Bugs - ```Atenção aos detalhes para não permitir erros inesperados```

## Materiais úteis

* [Link1](https://www.stone.com.br)
* [Link2](https://www.stone.com.br)
* [Link3](https://www.stone.com.br)
