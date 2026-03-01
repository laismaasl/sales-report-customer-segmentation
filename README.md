# sales-report-customer-segmentation
Relatório de Business Intelligence focado em análise de vendas globais e segmentação de clientes para suporte à decisão estratégica.

# 🛒 UK Merch: Inteligência de Vendas e Segmentação Estratégica (RFM)

## 📍 Índice de Navegação

1. [O Projeto](#o-projeto)
2. [Desafio e Perguntas de Negócio](#desafio-e-perguntas-de-negocio)
3. [Metodologia e Ciclo de Desenvolvimento](#metodologia-e-ciclo-de-desenvolvimento)
4. [Descrição das Variáveis do Dataset](#descricao-das-variaveis-do-dataset)
5. [Entregáveis](#entregaveis)
6. [Stack Tecnológica e Requisitos](#stack-tecnologica-e-requisitos)
7. [Análise de Métricas de Vendas](#analise-de-metricas-de-vendas)
8. [Diagnóstico de Faturamento e Retenção](#diagnostico-de-faturamento-e-retencao)
9. [Segmentação de Clientes usando RFM](#segmentacao-de-clientes-usando-rfm)
10. [Recomendações a UK Merch](#recomendacoes-a-uk-merch)


<a name="projeto"></a> 1. O Projeto

Análise exploratória e descritiva dos dados de vendas da UK Merch, uma empresa fictícia de varejo com operações globais. O objetivo foi transformar um dataset bruto de transações em um relatório executivo para suporte à decisão de marketing e logística.



<a name="desafio"></a> 2. Desafio e Perguntas de Negócio

O dashboard foi construído para responder a dores reais da operação:

Performance Financeira: Qual a média de vendas mensal e qual o mês de pico?
Concentração de Mercado: Como as vendas se desagregram por país?
Comportamento do Cliente: Quem são os clientes Top Tier e qual o ticket médio gasto?
Fidelização: Qual a porcentagem de recompra (retenção) vs. Churn?



<a name="metodologia"></a> 3. Metodologia e Ciclo de Desenvolvimento
(Descreva as etapas de limpeza e prazos)

Este projeto foi desenvolvido no contexto do curso da Laboratória em parceria com a IBM, utilizando metodologia ágil com Sprint de 6 dias.

Durante esse período, o desafio consistiu em:

Compreender o core do negócio (varejo internacional)
Aprender e aplicar os recursos do Google Sheets
Realizar o tratamento da base de dados
Construir análises estratégicas
Desenvolver o dashboard executivo
Gravar e apresentar o vídeo de apresentação do projeto (critério avaliativo)

🔎 Etapas do Ciclo de Desenvolvimento

1️⃣ Carregamento e Diagnóstico Inicial
Importação da base global
Identificação de inconsistências
Exclusão de 7.429 registros inconsistentes

2️⃣ Tratamento e Estruturação
Padronização de datas e moedas
Criação de colunas auxiliares
Cálculo de métricas (Receita, Ticket Médio, Frequência, Recência)

3️⃣ Análise Exploratória
Faturamento global e por país
Volume de vendas
Ticket médio por loja
Retenção anual
Identificação de sazonalidade

4️⃣ Modelagem RFM
Cálculo de Recência, Frequência e Valor
Classificação em segmentos estratégicos

5️⃣ Construção do Dashboard
KPIs principais
Mapas e comparativos internacionais
Indicadores de retenção
Segmentação visual por categorias
Recomendações estratégicas
Todo o projeto foi construído integralmente no Google Sheets, simulando um ambiente real de consultoria com prazo restrito e entrega executiva.


<a name="variaveis"></a> 4. Descrição das Variáveis do Dataset
(Liste as colunas da planilha)

| Variável | Descrição |
| :--- | :--- |
| **Nº da fatura** | Um número atribuído exclusivamente a cada transação. Se começar com "c", indica uma substituição. |
| **Data da fatura** | Data e hora da fatura, dia e hora em que a transação foi gerada. |
| **ID Cliente** | Número de clientes. Um número integral de 5 dígitos atribuído exclusivamente a cada cliente. |
| **País** | O nome do país onde cada cliente reside. |
| **Quantidade** | As quantidades de cada produto (item) por transação. |
| **Valor** | Valor da fatura em libras esterlinas. |


<a name="entregaveis"></a> 5. Entregáveis

📦 Entregáveis Técnicos
1- Base de dados tratada
Remoção de 7.429 registros inconsistentes
Padronização de datas e métricas
Estruturação para análise estratégica
2- Modelagem de KPIs
Faturamento global e por país
Ticket médio (AOV)
Volume de compras
Número de clientes ativos
Retenção anual (22,7%)
3- Dashboard Executivo Interativo (Google Sheets)
KPIs consolidados
Mapa global de faturamento
Ranking Top 5 países
Comparativo Reino Unido vs demais países
Sazonalidade de vendas
Ticket médio por região
Análise de oportunidade vs faturamento
Lei de Pareto
Segmentação RFM visual
4- Segmentação completa da base de clientes (RFM)
Classificação por Recência, Frequência e Valor
Categorização estratégica
Base pronta para ações de marketing direcionadas
5- Plano de recomendações estratégicas
Ações por segmento
Estratégia de retenção
Estratégia de expansão internacional
Foco em aumento de LTV
6- Vídeo de apresentação executiva
Apresentação estratégica do case
Storytelling orientado a negócios
Insigths das decisões analíticas



<a name="stack"></a> 6. Stack Tecnológica e Requisitos

Tratamento de Dados: Limpeza de dados nulos e padronização de moedas internacionais.
Segmentação de Clientes: Agrupamento por volume de compras e importância estratégica.
Análise Temporal: Identificação de sazonalidade nas vendas globais.
Dashboard Interativo: Centralização de KPIs como Qtd de Clientes, Qtd de Vendas e Taxas de Retenção.



<a name="metricas"></a> 7. Análise de Métricas de Vendas
A análise global revelou um comportamento de consumo consistente, com forte concentração no Reino Unido e oportunidades relevantes em mercados internacionais.

📊 Principais Indicadores

18.524 compras registradas
4.334 clientes ativos

Reino Unido:
16.646 compras
3.920 clientes

Demais países:
1.888 compras
414 clientes

🌍 Comportamento Global

O Reino Unido concentra o maior volume de vendas.
Países como Holanda, Irlanda, Alemanha, França e Austrália lideram o ranking fora do eixo principal.
Mercados como Singapura apresentam ticket médio elevado mesmo com menor volume de compras — indicando alto potencial estratégico.

Identificou-se sazonalidade clara em:
Períodos de entrada de coleção
Pré-Natal
Novembro como mês de maior pico de vendas

O comportamento global demonstra:
Forte dependência do mercado doméstico
Potencial de expansão internacional
Oportunidades de alavancagem via ticket médio



<a name="faturamento"></a> 8. Diagnóstico de Faturamento e Retenção
(Destaque os KPIs de faturamento e os 22,7% de retenção)

💰 Faturamento Anual Bruto
£ 8.897.991,60 (Total Global)
£ 7.298.806,28 — Reino Unido
£ 1.599.185,32 — Demais Países

O Reino Unido representa aproximadamente 82% do faturamento total, evidenciando forte concentração de receita.

🔁 Retenção
Retenção anual global: 22,70%
Reino Unido: 22,68%
Demais Países: 22,97%

A retenção apresenta comportamento semelhante entre mercados, indicando padrão consistente de recompra.
Entretanto, o índice sugere oportunidade clara de melhoria, especialmente considerando o potencial de clientes classificados como “hibernando”.

🎯 Ticket Médio
Ticket médio global: £303,00

Países como Singapura apresentam ticket médio superior à média global, o que reforça oportunidades de crescimento com foco em valor por cliente.



<a name="rfm"></a> 9. Segmentação de Clientes usando RFM

A segmentação foi construída com base no modelo RFM (Recency, Frequency, Monetary Value):

Recência (R): há quanto tempo o cliente realizou sua última compra
Frequência (F): número de compras realizadas
Valor Monetário (M): quanto o cliente gastou no período

A partir desses critérios, os clientes foram classificados em categorias estratégicas como:

🏆 Campeões (10,15%)
🔥 Potenciais Leais
💎 Promissores
⚠️ Em Risco
❄️ Hibernando (20,33%)
📈 Insights Relevantes

Clientes “Campeões” concentram alto ticket médio e forte recorrência.
Clientes “Hibernando” representam parcela significativa da base e baixo engajamento recente.
A aplicação da Lei de Pareto indica concentração relevante de receita em grupos estratégicos.
Essa segmentação permite ações direcionadas e personalizadas, substituindo abordagens genéricas.



<a name="recomendacoes"></a> 10. Recomendações a UK Merch
(Finalize com as ações estratégicas sugeridas)
Com base na análise, as seguintes ações estratégicas são recomendadas:

🎯 1. Estratégia por Segmento (Marketing Personalizado)
Campeões: programas VIP, acesso antecipado a coleções
Potenciais Leais: ofertas limitadas e incentivos de recompra
Em Risco: campanhas de reativação
Hibernando: comunicação personalizada com descontos estratégicos

🌍 2. Expansão Internacional Estratégica
Priorizar mercados com alto ticket médio (ex: Singapura)
Explorar Holanda e Irlanda como polos de crescimento
Analisar elasticidade de preço por região

📈 3. Aumento da Retenção
Programas de fidelização
Automação de e-mails segmentados
Acompanhamento por ciclo de vida do cliente

💡 4. Foco em LTV (Lifetime Value)
A personalização por categoria permite:
Aumentar tempo de permanência na base
Elevar ticket médio
Reduzir churn
Maximizar receita recorrente

📌 Conclusão
Toda a base foi categorizada estrategicamente, permitindo à UK Merch:
Melhorar ações de retenção
Otimizar campanhas de marketing
Personalizar atendimento
Expandir mercados de forma estruturada
Maximizar faturamento e eficiência operacional
