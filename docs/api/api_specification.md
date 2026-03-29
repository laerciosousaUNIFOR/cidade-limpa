# API do Sistema

## Autenticação
JWT (JSON Web Token)

## Endpoints

### Usuários
POST /usuarios  
POST /login  

### Problemas
POST /problemas  
GET /problemas  
GET /problemas/{id}  
PUT /problemas/{id}  
DELETE /problemas/{id}  

## Exemplo

POST /problemas

Request:
{
  "descricao": "Lixo acumulado",
  "localizacao": "Rua X"
}

Response:
{
  "id": 1,
  "status": "pendente"
}
