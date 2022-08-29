# Aplicando o estilo Arquitetural REST com Node.js

## Resumo

Microserviço de autenticação com JWT e CRUD de produtos.

A comunicação dos serviços se dá através de requisições HTTP. A solicitação envolve a autenticação com o microserviço de autenticação, onde o cliente entra com suas credenciais e recebe um token para autorização do consumo do microserviço de produtos.

## Endpoints

CRUD de usuários

```txt
GET /users
GET /users/:uuid
POST /users
PUT /users/:uuid
DELETE /users/:uuid
```

Autenticação

```txt
POST /token
POST /token/validate
```
