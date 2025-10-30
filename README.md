# 📊 TeamWork API Integration

Projeto de estágio curricular da Licenciatura em Informática (Redes e Cibersegurança) – Universidade da Maia (UMAIA)  
**Estudante:** Tiago Leal Baganha  
**Ano Letivo:** 2024/2025  
**Entidade Acolhedora:** Garland  


## 📘 Descrição do Projeto

Este projeto tem como objetivo o desenvolvimento de uma API que integra a plataforma de gestão de projetos **TeamWork** com a ferramenta de análise de dados **Power BI**, permitindo à empresa **Garland** centralizar, monitorizar e analisar informações de projetos de forma eficiente.

A solução extrai dados relevantes via TeamWork API, processa-os e armazena-os numa base de dados SQL, através de um micro ORM (Dapper), para posterior consulta em dashboards do Power BI.

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **.NET (C#)** – Backend da API
- **Dapper** – ORM para acesso a dados
- **SQL Server** – Armazenamento dos dados extraídos
- **Swagger** – Documentação dos endpoints
- **Bitbucket** – Versionamento de código
- **TeamWork API** – Fonte dos dados
- **Power BI** – Ferramenta de visualização de dados
- **SOA & BPEL** – Integração e orquestração de serviços

## 🧩 Estrutura do Projeto

/src
├── Api
├── Application
├── Domain
└── Infrastructure
/tests
/docs
README.md
.gitignore
.editorconfig
appsettings.json


## 🚀 Funcionalidades Principais

- Extração de tarefas e tempos da TeamWork API
- Tratamento de paginação, autenticação e estruturação de dados
- Inserção e atualização automática dos dados na base de dados
- Criação de jobs agendados para atualização diária
- Sistema de notificações por email em caso de falha
- Documentação interativa com Swagger

## 🧪 Testes

Foram desenvolvidos testes unitários para validar as funcionalidades críticas da API, com foco em:
- Tratamento de erros HTTP
- Validação de parâmetros
- Conexões com a base de dados

## 📦 Requisitos

- .NET 6.0 ou superior
- SQL Server
- Visual Studio / VS Code
- Conta e chave de API do TeamWork


## 📅 Planeamento
O desenvolvimento foi distribuído ao longo de 250 horas, seguindo um plano semanal iterativo, com validação frequente por parte da equipa técnica e académica.

## 📈 Resultados Esperados
Dashboards automatizados no Power BI com dados extraídos da TeamWork

Redução de trabalho manual na análise de performance de projetos

Centralização da informação de tarefas e tempos

## 🧠 Competências Desenvolvidas
Integração de APIs REST

Estruturação e manutenção de bases de dados relacionais

Programação orientada a serviços (SOA)

Automação de jobs e envio de alertas

Organização modular de projetos .NET
