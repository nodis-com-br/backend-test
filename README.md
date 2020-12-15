# Desafio {nome} - Python Developer

Olá, agradecemos o seu interesse em fazer parte desse super time!

O objetivo do desafio é entender o quanto você conhece sobre planejamento, codificação e monitoria. [Clique aqui](https://github.com/nodis-com-br/bushido) para ver quais são os valores e responsabilidades do nossos devs.

Fique à vontade para tentar quantas vezes quiser :smile:

## Instruções
* Crie um board público no [Trello](https://trello.com/) e organize as tarefas necessárias para finalizar o desafio.
* [Clique aqui](https://www.stone.com.br) para enviar o link do [Trello](https://trello.com/) e a estimativa de conclusão.
* Utilize Python :snake: para construir o desafio. Fique à vontade para escolher os frameworks, libs, banco de dados, etc.
* Versione o código em um repositório público aqui no Github.
* [Clique aqui](https://www.stone.com.br) para enviar o link do repositório. :trophy:
* Seu desafio será avaliado pelo nosso time de especialistas. Caso seja aprovado, agendaremos uma data para você apresentá-lo. #keepcalm

## Contexto

Boa parte dos pequenos varejistas não utilizam qualquer software para fazer a gestão do próprio catálogo de produtos. Isto acaba gerando uma enorme desorganização operacional e a consequência disso pode ser o fechamento da empresa. 

A necessidade é utilizar um software que permita cadastrar, atualizar, deletar e listar os produtos.

## Sua missão, caso deseje aceitá-la é:

Criar uma API para gestão de produtos.

Temos uma sugestão:

#### Product

Campo   | Tipo
--------- | ------
id | id
name | str (128)
gtin13 | str (13)
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

## Algumas regras

* Não permitir que um produto seja cadastrado com o gtin13 ou nome já existente.
* Não permitir que um produto seja adicionado com o preço menor ou igual a zero.
* Não permitir que um produto seja adicionado com a quantidade menor ou igual a zero.
* Não permitir uma redução de preço maior ou igual a 50% do valor atual.
* Não permitir que um produto deletado seja atualizado.

## O que você não pode esquecer

* Criar teste unitários
* Utilizar corretamente os verbos http
* Validar requisições
* Registrar log de erros (console, arquivo, etc)
* Persistir informações em um banco de dados
* Criar README com as instruções sobre como executar e testar o projeto
* Incluir na raiz do projeto uma collection do Postman com todas as requisições disponíveis

## O que será um diferencial

* Criar documentação (Swagger, ReDoc, etc)
* Registrar log de requisições e respostas (console, arquivo, etc)
* Disponibilizar endpoint para healthcheck
* Criar Dockerfile

## É faixa preta? (opcional)

[Clique aqui](https://www.stone.com.br) e fale um pouco sobre sua experiência com monitoria, performance e outros.

## O que será avaliado

#### Como você planejou

* Organização das tarefas - *A qualidade do planejamento será refletido na execução. Entenda o problema, crie as tarefas e estime com prazos realistas*
* Tamanho das tarefas - *Evite criar tarefas com estimativas enormes*
* Estimativa - *Registre qual é a estimativa em horas para finalizar as tarefas*
* Esforço - *Registre quantas horas você precisou para finalizar uma tarefa*
* Categorização das tarefas (codificação, teste, estudo, etc) - *Indique qual é o tipo de tarefa e saberemos onde você aplicou mais esforço*

#### Como você desenvolveu

* Flexibilidade - *Deve ser fácil incluir novas features, substituir ferramentas..*
* Testabilidade - *O código deve ser fácil de testar. [Leia mais](https://www.stone.com.br) sobre complexidade ciclomática*
* Simplicidade - *O código deve ser fácil de entender. [Leia mais](https://www.stone.com.br) sobre complexidade cognitiva*
* Performance - *Evite realizar chamadas desnecessárias ao banco de dados, encontre o benchmark das libs que você escolher..*
* Duplicação de código - *Reaproveite o máximo de código para evitar duplicações*
* Vulnerabilidades - *Evite deixar informações sensíveis no código (senhas, conn strings, etc)*
* Cobertura de testes - *Tente superar 70% de cobertura*
* Bugs - *Atenção aos detalhes para não permitir erros inesperados*

## Isso vai te ajudar

* [Link1](https://www.stone.com.br)
* [Link2](https://www.stone.com.br)
* [Link3](https://www.stone.com.br)

Encontrou algum material diferente que te ajudou no desafio? [Clique aqui](https://www.stone.com.br) e compartilhe com a gente :pray:
