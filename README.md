# Alura-Telecom-X-
Telecom x Projeto de Data Science com foco na identificação de perfis de clientes com maior propensão ao cancelamento (churn). Utiliza técnicas de limpeza de dados, análise exploratória, codificação de variáveis, normalização, clusterização (KMeans) e visualizações para gerar insights acionáveis para retenção de clientes.


# Análise de Churn de Clientes – Telecom

## Sobre o Projeto
Este projeto tem como objetivo identificar padrões de cancelamento (churn) de clientes em uma empresa de telecomunicações. A partir de dados reais, foram aplicadas técnicas de ciência de dados para entender os fatores que influenciam o desligamento de clientes e propor estratégias de retenção.

## Etapas do Projeto

- Carregamento e limpeza dos dados
- Análise Exploratória de Dados (EDA)
- Agrupamento por mês e análise de gastos
- Clusterização com KMeans para segmentação de clientes
- Identificação dos perfis com maior churn
- Geração de gráficos e insights acionáveis

## Principais Conclusões

- Método de pagamento com maior índice de churn: fatura digital e Electronic check.
- Ausência de cônjuge ou filhos aumenta a taxa de cancelamento em até 20%.
- Clientes seniores apresentam, em média, 40% a mais de cancelamentos.
- Contratos do tipo "mensal" têm o maior índice de churn entre todos os perfis.
- Internet via fibra ótica tem maior número de cancelamentos, especialmente entre seniores.
- O valor do plano mensal não interfere diretamente na fidelidade do cliente.
- Algumas variáveis não mostraram impacto significativo no churn:  
  gênero, dependentes, serviço de telefone, linhas múltiplas, segurança online, backup, proteção de dispositivo, suporte técnico, streaming de TV, streaming de filmes.

## Principais Insights

- Perfis com maior churn combinam contratos mensais, internet fibra, fatura digital e pagamento via electronic check.
- A presença de familiares é um fator importante na retenção de clientes.
- Clientes mais velhos com alta exposição a contratos instáveis tendem a cancelar mais.
- Segmentações via clusterização ajudam a entender melhor os comportamentos de diferentes grupos e podem direcionar ações específicas de retenção.

## Tecnologias Utilizadas

- Python (Pandas, Seaborn, Matplotlib, Scikit-Learn)
- Jupyter Notebook
- Análise estatística e visualizações

## Como Executar o Projeto

1. Clone este repositório:
   ```bash

   git clone https://github.com/NeuroL2/Alura-Telecom-X
