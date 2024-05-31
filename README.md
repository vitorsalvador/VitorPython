﻿# VitorPython

## Product API

### Pré-requisitos

- Docker
- Docker Compose

### Executando a Aplicação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/product-api.git
cd product-api

2. Inicie a aplicação com Docker Compose:

docker-compose up


A aplicação estará disponível em http://localhost:5000.

Endpoints
GET /products
GET /products/{id}
POST /products
PUT /products/{id}
DELETE /products/{id}
Autenticação: /auth/register e /auth/login
Documentação da API
A documentação Swagger estará disponível em http://localhost:5000/swagger.

Executando os Testes
Execute os testes automatizados com:
docker exec -it product-api_web_1 pytest
