# Sistema de Análise de Ações na Bolsa de Valores

## Visão Geral

Este projeto é uma plataforma para análise de ações da bolsa de valores, com backend em FastAPI, banco de dados PostgreSQL, frontend com Bootstrap e Chart.js, e suporte para Docker.

## Estrutura do Projeto

- **Backend**: FastAPI para APIs REST
- **Banco de Dados**: PostgreSQL
- **Frontend**: HTML, Bootstrap, Chart.js
- **Orquestração**: Docker e Docker Compose

## Como Executar

1. Certifique-se de ter o Docker e o Docker Compose instalados.
2. No diretório raiz, execute:

```bash
docker-compose up --build
```

3. Acesse os serviços:
   - **API**: [http://localhost:8000](http://localhost:8000)
   - **Frontend**: [http://localhost:8080](http://localhost:8080)

## Tecnologias Utilizadas

- **Backend**: Python, FastAPI
- **Banco de Dados**: PostgreSQL
- **Frontend**: Bootstrap, Chart.js
- **Infraestrutura**: Docker, Docker Compose

## Estrutura de Diretórios

- `backend/`: Código do backend
- `frontend/`: Código do frontend
- `database/`: Configuração do banco de dados
- `docker/`: Configuração do Docker Compose

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.