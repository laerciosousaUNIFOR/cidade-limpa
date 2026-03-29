# Modelo de Dados

## Entidades

### Usuario
- id (PK)
- nome
- email
- senha

### Problema
- id (PK)
- descricao
- status
- imagem
- localizacao
- data_criacao
- id_usuario (FK)

## Relacionamentos
Um usuário pode registrar vários problemas (1:N)
