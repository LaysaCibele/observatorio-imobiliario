# Observatório Imobiliário

Uma plataforma de Ciência de Dados para análise do mercado imobiliário, previsão de preços e geração de insights com Machine Learning, Inteligência Artificial e automação.

## Sobre o projeto

O Observatório Imobiliário é um projeto end-to-end que combina análise de dados, SQL, Machine Learning, APIs, Business Intelligence, AI Agent e automação.

A plataforma utiliza dados imobiliários para identificar padrões, analisar fatores que influenciam os preços, realizar previsões e gerar insights sobre o mercado.

O projeto também contará com um agente de IA capaz de responder perguntas em linguagem natural, consultar dados e executar análises, além de automações com n8n para monitoramento e geração de insights.

## Funcionalidades

* Análise exploratória e identificação de tendências.
* Análise de preços por localização e características dos imóveis.
* Previsão de preços utilizando Machine Learning.
* Comparação entre preço anunciado e preço estimado.
* Armazenamento e consultas utilizando SQL.
* API para realização de previsões.
* Dashboards e visualizações.
* AI Agent para consultas e análises em linguagem natural.
* Automação de monitoramento, alertas e geração de insights com n8n.

## Arquitetura

```text
Dados de Imóveis
       ↓
Processamento e Análise
       ↓
Banco de Dados
       ↓
 ┌─────┼──────────┐
 ↓     ↓          ↓
BI    ML      AI Agent
       ↓       ↙ ↓ ↘
    API      SQL Python
       ↓        ↓
   Previsões   n8n
                 ↓
        Automação e Monitoramento
```

## Tecnologias

* Python
* Pandas
* NumPy
* SQL e SQLite
* Scikit-learn
* FastAPI
* Matplotlib, Seaborn e Plotly
* Metabase
* LLMs
* n8n
* Git e GitHub

## Dataset

O projeto utilizará dados públicos sobre apartamentos em Curitiba, incluindo informações como características, localização, comodidades e preços.

O desenvolvimento será progressivo, começando pela análise e preparação dos dados e evoluindo para Machine Learning, API, BI, Inteligência Artificial e automação.

## Autora

**Laysa Cibele**

Estudante de Ciência da Computação e IA | Estagiária em Ciência de Dados.
