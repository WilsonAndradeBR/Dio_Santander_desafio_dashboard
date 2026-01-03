
# Dio/Santander desafio: Dashboard

O objetivo do desafio é criar uma **dashboard de vendas** com _Microsoft Excel_, transformando a base de dados em informações visuais para análise.

O projeto simula a análise de vendas de assinaturas do **_NBA League Pass_**, o serviço de streaming de partidas de basquetebol da **NBA**. Para isso temos uma base de dados de assinantes detalhando os respectivos tipos de assinaturas de cada plano. Tanto os assinantes quanto os tipos de planos e respectivos valores são fictícios.

## Os Planos

Há quatro (04) opções de planos:
- **League Pass**
- **League Pass Premium**
- **Team Pass**
- **NBA TV**

Cada plano possui três (03) modalidades de assinatura, exceto **_Team Pass_** e **_NBA TV_**, que possuem apenas duas modalidades:

| **Plano**               | Monthly | Regular Season | Full Season |
|---------------------|---------|----------------|-------------|
| **League Pass**         | R$54,90 | R$349,90       | R$449,90    |
| **League Pass Premium** | R$74,90 | R$489,90       | R$599,90    |
| **Team Pass**           | R$39,90 | --             | R$299,90    |
| **NBA TV**              | R$24,90 | --             | R$199,90    |

## Os dados

A base de dados é uma lista com 200 assinantes fictícios com as seguintes informações:
- ID de assinatura
- Nome
- Gênero
- Cidade/Região
- Plano adquirido
- Data de início
- Tipo de assinatura
- Preço da assinatura (R$)
- Time favorito

## O painel

O objetivo do dashboard é apresentar os resultados de **vendas totais** e para cada **modadidade de assinatura**, que podem ser filtrados por tipo de plano:
- League Pass
- League Pass Premium
- Team Pass
- NBA TV

Conforme filtra-se o plano, os gráficos apresentam os resultados de vendas das **modadidade de assinatura**, **vendas por região do Brasil** e **vendas por gênero**.

Os _Big Numbers_ são fixos e apresentam os resultados de vedas de todos os planos.