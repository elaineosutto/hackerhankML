# Backend API - HackerRank Challenge

## Descrição
API REST para gerenciamento de modelos.

## Endpoints

- POST /model → cria um modelo
- GET /model → lista todos
- GET /model/{id} → busca por id
- DELETE /model/{id} → remove por id
- DELETE /erase → remove todos

## Tecnologias
- Java
- Spring Boot
- JPA / H2 (in-memory)

## Decisões
- Uso de arquitetura em camadas (Controller, Service, Repository)
- Tratamento de erros com exceptions customizadas