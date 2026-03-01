# sales-report-customer-segmentation
Relatório de Business Intelligence focado em análise de vendas globais e segmentação de clientes para suporte à decisão estratégica.

# 🛒 UK Merch: Inteligência de Vendas e Segmentação Estratégica (RFM)

![Category: Business Intelligence](https://img.shields.io/badge/Category-Business_Intelligence-blue)
![Methodology: RFM](https://img.shields.io/badge/Methodology-RFM_Analysis-purple)
![Tool: Google_Sheets](https://img.shields.io/badge/Tool-Google_Sheets-green)

## 📍 Índice de Navegação

1. [O Projeto](#o-projeto)
2. [Desafio e Perguntas de Negócio](#desafio)
3. [Metodologia e Ciclo de Desenvolvimento](#metodologia)
4. [Descrição das Variáveis do Dataset](#variaveis)
5. [Entregáveis](#entregaveis)
6. [Stack Tecnológica e Requisitos](#stack)
7. [Análise de Métricas de Vendas](#metricas)
8. [Diagnóstico de Faturamento e Retenção](#faturamento)
9. [Segmentação de Clientes usando RFM](#rfm)
10. [Recomendações a UK Merch](#recomendacoes)

---

## <a name="o-projeto"></a> 📖 1. O Projeto
Análise exploratória e descritiva dos dados de vendas da **UK Merch**, uma empresa de varejo com operações globais. O objetivo central foi transformar um dataset bruto de transações em um **relatório executivo dinâmico** para suporte à decisão estratégica em marketing e logística.

---

## <a name="desafio"></a> 🎯 2. Desafio e Perguntas de Negócio
O dashboard foi projetado para solucionar dores reais da operação através de quatro pilares:

* **Performance Financeira:** Qual a média de vendas mensal e os meses de pico?
* **Concentração de Mercado:** Como as vendas se desagregram geograficamente?
* **Comportamento do Cliente:** Quem são os clientes *Top Tier* e qual o ticket médio?
* **Fidelização:** Qual a taxa de retenção anual vs. Churn?

---

## <a name="metodologia"></a> 🛠️ 3. Metodologia e Ciclo de Desenvolvimento
Projeto desenvolvido sob **metodologia ágil (Sprint de 6 dias)** em parceria com a **Laboratória e IBM**.

### 🔎 Etapas do Ciclo
1.  **Diagnóstico:** Importação da base global e exclusão de **7.429 registros inconsistentes**.
2.  **Tratamento:** Padronização de datas/moedas e criação de colunas de Recência, Frequência e Valor.
3.  **Análise Exploratória:** Identificação de sazonalidade e análise de faturamento por país.
4.  **Modelagem RFM:** Classificação da base em segmentos estratégicos.
5.  **Visualização:** Construção de dashboard interativo no Google Sheets com foco executivo.

---

## <a name="variaveis"></a> 📋 4. Descrição das Variáveis
| Variável | Descrição |
| :--- | :--- |
| **Nº da fatura** | ID exclusivo da transação (iniciado em "c" indica substituição). |
| **Data da fatura** | Timestamp da geração da transação. |
| **ID Cliente** | Identificador único de 5 dígitos por cliente. |
| **País** | Local de residência do cliente. |
| **Quantidade** | Volume de itens por transação. |
| **Valor** | Valor da fatura em Libras Esterlinas (£). |

---

## <a name="entregaveis"></a> 📦 5. Entregáveis
* **Base Tratada:** Dados limpos e padronizados prontos para escala.
* **Modelagem de KPIs:** Faturamento, AOV (Ticket Médio) e Taxa de Retenção.
* **Dashboard Interativo:** Mapa global, ranking de países e indicadores de Pareto.
* **Segmentação RFM:** Base categorizada para campanhas de marketing direcionadas.
* **Vídeo de Apresentação:** Storytelling orientado a negócios com foco em decisões analíticas.

---

## <a name="stack"></a> 💻 6. Stack Tecnológica
* **Ferramenta Principal:** Google Sheets (Fórmulas Avançadas, QUERY, VLOOKUP).
* **Técnicas:** Limpeza de dados nulos, análise temporal e segmentação de clusters.

---

## <a name="metricas"></a> 📊 7. Análise de Métricas de Vendas
A análise revelou um volume total de **18.524 compras** realizadas por **4.334 clientes**.

* **Domínio Geográfico:** O Reino Unido concentra 16.646 compras (aprox. 90% do volume transacional).
* **Top 5 Internacional:** Holanda, Irlanda, Alemanha, França e Austrália lideram a expansão.
* **Sazonalidade:** Pico histórico de vendas em **Novembro**, impulsionado por trocas de coleção e antecipação de feriados.

---

## <a name="faturamento"></a> 💰 8. Diagnóstico de Faturamento e Retenção
* **Faturamento Bruto:** **£ 8.897.991,60** (Global).
* **Distribuição:** Reino Unido (£ 7,29M) vs. Internacional (£ 1,59M).
* **Retenção Global:** **22,70%** (indicando forte padrão de recompra, mas com alta margem para otimização).
* **Destaque Estratégico:** **Singapura** apresenta ticket médio superior à média global de **£ 303**, indicando potencial de expansão premium.

---

## <a name="rfm"></a> 👥 9. Segmentação de Clientes (RFM)
Utilização do modelo de Recência, Frequência e Valor para categorizar a base:

* 🏆 **Campeões (10,15%):** Clientes de alta frequência e alto gasto.
* ❄️ **Hibernando (20,33%):** Parcela significativa da base com baixo engajamento recente.
* **Lei de Pareto:** Identificação da pequena parcela de clientes que gera a maior parte da receita líquida.

---

## <a name="recomendacoes"></a> 🚀 10. Recomendações Estratégicas
1.  **Marketing Personalizado:** Abandonar comunicações globais e focar em programas VIP para "Campeões" e campanhas de reativação para clientes "Em Risco".
2.  **Expansão por Valor:** Priorizar mercados como Singapura para maximizar o ROI via Ticket Médio.
3.  **Foco em LTV:** Implementar automações de e-mail baseadas no ciclo de vida para reduzir o Churn.
4.  **Fidelização:** Criar incentivos específicos para o segmento "Potenciais Leais" visando transformá-los em "Campeões".

---
