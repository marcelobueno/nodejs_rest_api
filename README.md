# API REST | NodeJS + MongoDB
Projeto desenvolvido em aula com o intuito de construir uma API REST de usuários usando NodeJS e MongoDB com Docker.

Este projeto tem como dependência:

- Express
- Mongoose
- BcryptJS

## Instalação
1- Clone o projeto
```
    git clone https://github.com/marcelobueno/nodejs_rest_api.git
```
2- Instale as dependências
```
    yarn install
```
3- Suba o docker com mongoDB.
```
    docker run --name nomedainstancia -d -p 27017:27017 mongo:latest
```
4- Inicialize o projeto
```
    yarn dev
```
## Rotas

**Post** /user (Cadastra um usuário).
**Get** /users (Busca todos os usuários cadastrados).

Pronto, agora o sistema já está disponível para testes nas rotas descritas acima. =)