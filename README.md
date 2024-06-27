# Teste Desenvolvedor PHP Pleno

Olá caro candidato, através deste teste iremos analisar seu conhecimento geral e velocidade de desenvolvimento.

## Instruções

Implementar uma aplicação web utilizando o framework Laravel ou codeigniter, banco de dados relacional Mysql ou Postgres, para persistir a inscrição de lutadores a torneios de artes marciais.

Sua aplicação deve possuir:

- CRUD de torneios:
	- Criar, editar, excluir e listar torneios.
	- O torneio deve conter titulo, tipo "exibição" ou "competição", data e hora de inscrição, data e hora de inicio, qtd max de participantes, valor do premio e local.
	- Deve ser ser possível pausar um torneio, impedindo novas inscrições.
- CRUD de lutadores:
	- Criar, editar, excluir e listar lutadores.
	- Deve conter nome, estilo de luta, altura, peso e gênero.
- Cada CRUD precisa:
	- Possuir formulários para criação e atualização.
	- Utilizar sempre soft delete.
	- Implementar validações de campos obrigatórios e tipos de dados.
- Regras de inscrição
	- Na listagem de torneios um botão deve efetivar a inscrição.
	- Um lutador pode se inscrever em um ou mais torneios.
	- Possibilitar inscrição apenas em torneios ativos(não pausados), que ainda não tenham atingido a qtd máxima de participantes e que a inscrição seja feita após a "data e hora de inscrição" e inferior a "data e hora de inicio".
- Cada Listagem deve:
	- Ser filtrável e ordenável por qualquer campo; 
	- Possuir paginação de 10 itens.

## Banco de dados

- O banco de dados deve ser criado utilizando migrations, e utilizar Seeds e Factorys para popular as tabelas(se estiver utlilizando Laravel), ou adicionar um .sql na raiz do projeto contendo o DDL e DML.

## Tecnologias a serem utilizadas

- PHP
- HTML
- CSS
- Javascript
- Framework Laravel (PHP) ou Codeigniter 3.1
- Docker (construção do ambiente de desenvolvimento)
- Mysql ou Postgres

## Entrega

- Crie um repo no github;
- Na raiz do projeto adicione a um arquivo readme.md com as informações necessárias para executar seu teste (comandos, migrations, factorys, e seeds caso tenha criado), bem como comandos docker;
- Ao finalizar, envie-nos o link do repositório;

## Diferencial

- API Rest JSON para todos os CRUDS.
- Permitir deleção em massa de itens nos CRUDs.
- Permitir que o usuário mude o número de itens por página.
- Implementar autenticação de usuário na aplicação.

## O que iremos analisar

- Organização e legibilidade do código;
- Aplicação de design patterns; 
- Criação do ambiente com Docker;

### Boa sorte!
