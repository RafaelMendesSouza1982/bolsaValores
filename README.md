# 📊 Sistema de Análise de Ações na Bolsa de Valores

## 🌟 Visão Geral

Este projeto é uma plataforma para análise de ações da bolsa de valores, com backend em FastAPI, banco de dados PostgreSQL, frontend com Bootstrap e Chart.js, e suporte para Docker. Ele permite ingestão de dados de mercado, cálculo de indicadores técnicos, backtesting de estratégias e visualização dos resultados via dashboard web.

## 🏗️ Estrutura do Projeto

- **Backend**: FastAPI para APIs REST
- **Banco de Dados**: PostgreSQL
- **Frontend**: HTML, Bootstrap, Chart.js
- **Orquestração**: Docker e Docker Compose

## 🚀 Funcionalidades Principais

- 📈 Coleta e armazenamento de dados históricos de ações
- 📊 Processamento de grandes volumes de dados financeiros
- 🔢 Cálculo automático de indicadores técnicos
- 🧪 Execução de backtesting de estratégias
- 🌐 Exposição de resultados via API REST
- 🖥️ Dashboard web para visualização

## 🛠️ Como Executar

1. Certifique-se de ter o Docker e o Docker Compose instalados.
2. No diretório raiz, execute:

```bash
docker-compose up --build
```

3. Acesse os serviços:
   - **API**: [http://localhost:8000](http://localhost:8000)
   - **Frontend**: [http://localhost:8080](http://localhost:8080)

## 🧰 Tecnologias Utilizadas

- **Backend**: Python 3.11+, FastAPI, Pydantic
- **Análise de Dados**: Pandas, NumPy, TA-Lib, Backtrader
- **Banco de Dados**: PostgreSQL, SQLAlchemy, Alembic
- **Frontend**: HTML5, CSS3, Bootstrap 5, Chart.js
- **Infraestrutura**: Docker, Docker Compose, Nginx

## 📂 Estrutura de Diretórios

- `backend/`: Código do backend
- `frontend/`: Código do frontend
- `database/`: Configuração do banco de dados
- `docker/`: Configuração do Docker Compose

## 🔮 Próximos Passos

- 🔒 Implementar autenticação JWT e controle de acesso
- ⚙️ Adicionar workers para processamento assíncrono
- 🛠️ Criar endpoints REST adicionais para cálculo de indicadores e backtesting
- 📋 Configurar logs estruturados e healthchecks