# Desafio {nome} - Python Developer

Olá, agradecemos o seu interesse em fazer parte desse super time!

O objetivo do desafio é entender o quanto você conhece sobre planejamento, codificação e monitoria. [Clique aqui](https://github.com/nodis-com-br/bushido) para ver quais são os valores e responsabilidades dos nossos devs.

Fique à vontade para tentar quantas vezes quiser :muscle:

## Instruções
* Crie um repositório aqui no Github para versionar seu código.
* Crie um projeto do tipo ```Basic Kanban``` e organize as tarefas necessárias para finalizar o desafio.
* [Clique aqui](https://www.stone.com.br) para enviar o link do repositório e a estimativa de conclusão.
* Utilize Python :snake: para construir o desafio. Fique à vontade para escolher os frameworks, libs, banco de dados, etc.
* [Clique aqui](https://www.stone.com.br) quando terminar de codificar. :trophy:
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
[gtin13](https://www.gs1br.org/codigos-e-padroes/chaves-de-identificacao/gtin) | str (13)
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

* Não permitir que um produto seja cadastrado com o [gtin13](https://www.gs1br.org/codigos-e-padroes/chaves-de-identificacao/gtin) ou nome já existente.
* Não permitir que um produto seja adicionado com o preço menor ou igual a zero.
* Não permitir que um produto seja adicionado com a quantidade menor ou igual a zero.
* Não permitir uma redução de preço maior ou igual a 50% do valor atual.
* Não permitir que um produto deletado seja atualizado.

## O que você não pode esquecer

* **Criar testes unitários.**
* **Definir corretamente os verbos e rotas da API.** 
* **Validar requisições:** Tamanho da string, inteiro menor que zero, etc. Retorne respostas claras quando a requisição for inválida.
* **Logar requisições, respostas e erros:** Arquivo, Console..
* **Persistir informações em um banco de dados:** PostgreSQL, MySQL, MongoDB..
* **Criar README:** Incluir instruções sobre como executar e testar o projeto
* **Criar Collection no Postman:** Incluir arquivo na raiz do projeto com o nome ```postman.json```

## O que será um diferencial

* **Criar documentação:** Swagger, ReDoc.. Dê preferência a documentação automática.
* **Disponibilizar Health Check.**
* **Criar Dockerfile e Docker Compose.**

## É faixa preta? (opcional)

[Clique aqui](https://www.stone.com.br) e fale um pouco sobre sua experiência com monitoria, performance e outros.

## O que será avaliado

### Como você planejou

* **Organização:** A qualidade do planejamento será refletido na execução. Entenda o problema, crie as tarefas e estime com prazos realistas
* **Tamanho das tarefas:** Evite criar tarefas com estimativas enormes
* **Estimativa:** Registre qual é a estimativa em horas para finalizar as tarefas
* **Esforço:** Registre quantas horas você precisou para finalizar uma tarefa
* **Categorização:** Indique qual é o tipo de tarefa (codificação, teste, estudo, etc) e saberemos onde você aplicou mais esforço

### Como você desenvolveu

* **Flexibilidade:** Deve ser fácil incluir novas features, substituir ferramentas..
* **Testabilidade:** O código deve ser fácil de testar. [Leia mais](https://medium.com/php-brasil/complexidade-ciclom%C3%A1tica-454191081681) sobre complexidade ciclomática
* **Cobertura de testes:** Tente superar 70% de cobertura
* **Simplicidade:** O código deve ser fácil de entender. [Leia mais](https://artesoftware.com.br/2019/02/10/complexidade-cognitiva/) sobre complexidade cognitiva
* **Performance:** Evite realizar chamadas desnecessárias ao banco de dados, encontre o benchmark das libs que você escolher..
* **Duplicação de código:** Reaproveite o máximo de código para evitar duplicações
* **Vulnerabilidades:** Evite deixar informações sensíveis no código (senhas, conn strings, etc)
* **Bugs:** Atenção aos detalhes para não permitir erros inesperados

## Isso vai te ajudar

* [API em Flask](https://lucassimon.com.br/2018/06/serie-api-em-flask---parte-1---introducao-configuracao-e-hello-world/)
* [Design Patterns](https://github.com/kelvins/design-patterns-python)
* [Primeiros passsos com testes unitários](http://devfuria.com.br/python/tdd-primeiros-passos-com-testes-unitarios/)
* [IoC e Injeção de Dependência](https://www.youtube.com/watch?v=A_rPxoNO3-c)
* [Docker Compose: O que é?](https://imasters.com.br/banco-de-dados/docker-compose-o-que-e-para-que-serve-o-que-come)

Encontrou algum material que te ajudou no desafio? [Clique aqui](https://www.stone.com.br) e compartilhe :pray:
