# Desafio {nome} - Python Engineer

## Instruções
* Criar um board público no [Trello](https://trello.com/) e organizar as tarefas necessárias para finalizar o desafio.
* Enviar link do [Trello](https://trello.com/) e a estimativa de conclusão para {email}
* Utilizar Python :snake: para construir o desafio. Sinta-se a vontade para escolher o framework, libs, banco de dados, etc.
* Versionar o código em um repositório público (Github)
* Enviar link do repositório para {email} quando terminar. :trophy:
* Caso seu projeto seja aprovado, você terá que apresentá-lo para um de nossos especialistas, ok?

## Contexto

O cliente gerencia sua loja sozinho
Precisa de um software para catalogar seus produtos
Criar
Atualizar nome, descrição, preço, quantidade
Deletar
Listar

## Sua missão, caso deseje aceitá-la é:

 Criar uma API 

#### Product

Campo   | Tipo
--------- | ------
id | id
name | str (128)
description | str (1024)
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
* Persistir informações em um banco de dados (relacional ou não relacional)
* Criar README com as instruções sobre como executar e testar o projeto
* Criar collection no Postman com as requisições

## O que será um diferencial

* Criar documentação (swagger, redoc, etc)
* Registrar log de requisições (console, arquivo, etc)
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

* Organização
* Tamanho das tarefas
* Categorização das tarefas (codificação, teste, etc)

#### Como você desenvolveu

* Simplicidade e testabilidade do código - O código deve ser fácil de entender e testar
* Duplicação de código - Reaproveite o máximo de código para evitar duplicações. >3% = RUIM, <3% = BOM
* Vulnerabilidades - Evite deixar informações sensíveis no código (senhas, conn strings, etc)
* Cobertura de testes - <30% = RUIM, 30 a 69% = RAZOÁVEL, 70 a 89% = BOM, >=90% = EXCELENTE
* Bugs - >1 = RUIM, 0 = BOM

## Materiais úteis

* [Link1](https://www.stone.com.br)
* [Link2](https://www.stone.com.br)
* [Link3](https://www.stone.com.br)
