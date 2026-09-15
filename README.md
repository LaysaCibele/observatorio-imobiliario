# 🏠 Observatório Imobiliário

Uma plataforma de **Ciência de Dados** voltada à análise do mercado imobiliário, identificação de padrões, previsão de preços e geração de insights utilizando **Machine Learning e Inteligência Artificial**.

## Sobre o projeto

O **Observatório Imobiliário** é um projeto end-to-end que combina **análise de dados, SQL, Machine Learning, APIs, Business Intelligence e Inteligência Artificial** em uma única aplicação.

A plataforma utiliza dados públicos do mercado imobiliário para explorar características dos imóveis, analisar fatores relacionados aos preços, identificar padrões e realizar previsões utilizando modelos de Machine Learning.

O projeto também contará com um **Agente de IA capaz de interagir com os dados em linguagem natural**, realizando consultas, análises e utilizando modelos de Machine Learning para responder perguntas e gerar insights sobre o mercado imobiliário.

## Funcionalidades

* Análise exploratória dos dados e identificação de tendências.
* Análise de preços por localização e características dos imóveis.
* Previsão de preços utilizando Machine Learning.
* Comparação entre preço anunciado e preço estimado.
* Armazenamento e consultas utilizando SQL.
* API para realização de previsões.
* Dashboards e visualizações interativas.
* AI Agent para consultas e análises em linguagem natural.
* Utilização de SQL, Python e modelos de Machine Learning como ferramentas do agente.
* Containerização da aplicação utilizando Docker.

## Arquitetura

```text
                 Dados de Imóveis
                        ↓
              Processamento e EDA
                        ↓
                 Banco de Dados
                        ↓
          ┌─────────────┼─────────────┐
          ↓             ↓             ↓
         BI             ML        AI Agent
                        ↓          ↙  ↓  ↘
                       API       SQL Python ML
                        ↓
                   Previsões
                        ↓
                      Docker
```

O **AI Agent** funciona como uma camada de interação em linguagem natural, podendo utilizar diferentes ferramentas de acordo com a pergunta realizada.

Exemplos:

```text
"Qual bairro possui o maior preço médio por m²?"
                    ↓
                   SQL
                    ↓
                Resposta
```

```text
"Qual é a relação entre área e preço?"
                    ↓
              Python / Análise
                    ↓
                Resposta
```

```text
"Quanto esse imóvel deveria custar?"
                    ↓
            Modelo de Machine Learning
                    ↓
                Previsão
```

## 🛠️ Tecnologias

### Dados e Machine Learning

* Python
* Pandas
* NumPy
* Scikit-learn

### Banco de Dados

* SQL
* SQLite

### Visualização e Business Intelligence

* Matplotlib
* Seaborn
* Plotly
* Metabase

### API e Aplicação

* FastAPI
* Docker

### Inteligência Artificial

* LLMs
* AI Agents
* Tool Calling
* Integração com SQL, Python e Machine Learning

### Desenvolvimento

* Git
* GitHub

## Dataset

O projeto utilizará dados públicos sobre **apartamentos em Curitiba**, contendo informações relacionadas às características dos imóveis, localização, comodidades e preços.

O desenvolvimento será realizado de forma progressiva, partindo da exploração e preparação dos dados e evoluindo para:

```text
Dados
  ↓
EDA
  ↓
SQL
  ↓
Machine Learning
  ↓
API
  ↓
Docker
  ↓
BI
  ↓
AI Agent
```

Cada tecnologia será incorporada conforme sua necessidade dentro da aplicação, mantendo o projeto focado em problemas reais de **Ciência de Dados e Inteligência Artificial**.

## Objetivo

O objetivo do projeto é construir uma aplicação completa que demonstre, de ponta a ponta, a utilização de diferentes conceitos e ferramentas de **Data Science, Machine Learning e Inteligência Artificial**.

Além de analisar dados imobiliários, o projeto busca explorar como modelos preditivos e agentes de IA podem ser utilizados para transformar dados em análises e respostas úteis.

## 👩‍💻 Autora

**Laysa Cibele**

Estudante de Ciência da Computação e IA | Estagiária em Ciência de Dados.

Projeto desenvolvido para fins de **estudo, portfólio e aprendizado prático em Ciência de Dados, Machine Learning e Inteligência Artificial**.
