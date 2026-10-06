# Alexandre Santos

Analista de dados com formação em Ciências Contábeis e especializações em Ciência de Dados, Engenharia da Computação e IA. Trabalho principalmente com SQL, Python e Databricks, e gosto de projetos em que a análise termina em uma decisão concreta: cortar um desconto, priorizar um SKU, agir sobre um segmento de churn.

[Portfólio](https://portfoliosantos.lovable.app/) · [LinkedIn](https://www.linkedin.com/in/alexandresantosdata/)

## Projetos

Em cada linha indico de onde vêm os dados. Quando são simulados ou fictícios, está dito.

| Projeto | Pergunta | Dados | O que encontrei |
|---|---|---|---|
| [superstore-sales-dashboard](https://github.com/AlexandreSantosRodrigues/superstore-sales-dashboard) ([dashboard](https://dbc-487363e2-3add.cloud.databricks.com/dashboardsv3/01f1be8f35cf1b5cb74fbcc33ef34b11/published?o=7474654958318993)) | Onde a margem está sendo perdida? | Kaggle Superstore, 9.994 transações | Margem geral de 12,47%. Itens com desconto acima de 20% somam cerca de US$ 135 mil de prejuízo. Mesas e estantes operam com margem negativa (-8,6% e -3,0%). |
| [telco-churn-sql-analysis](https://github.com/AlexandreSantosRodrigues/telco-churn-sql-analysis) | Quem cancela? | Kaggle Telco, 7.043 clientes | Churn geral de 26,5%. Contrato mensal com pagamento por electronic check chega a 53,7% (1.850 clientes). |
| [hr-analytics-turnover-databricks](https://github.com/AlexandreSantosRodrigues/hr-analytics-turnover-databricks) | O que explica a saída de funcionários? | IBM HR Attrition, 1.470 registros | Atrito de 16,1%. Quem tem até 1 ano de casa sai 34,9% das vezes; salário até 3k, 28,6% contra 3,8% acima de 15k. |
| [ga4-multi-touch-attribution](https://github.com/AlexandreSantosRodrigues/ga4-multi-touch-attribution) | Last-click, linear e time-decay contam a mesma história? | GA4 e-commerce público no BigQuery, 4,3 mi de eventos e 5.692 compras | Em google/cpc o modelo linear atribui 202 conversões contra 165 no last-click (+22%). Só SQL, sem custo. |
| [white-spots-rj](https://github.com/AlexandreSantosRodrigues/white-spots-rj) ([dashboard](https://datastudio.google.com/s/rZ7pUd7whek)) | Onde há muito público e pouca concorrência? | Censo 2022 (IBGE) e OpenStreetMap, 162 bairros | Score 0–100 (60% densidade de público, 40% ausência de concorrência, raio de 2 km). PoC aplicada a varejo de moda. |
| [Monitoramento_Brent](https://github.com/AlexandreSantosRodrigues/Monitoramento_Brent) | Como calcular a paridade do Brent em reais sem planilha manual? | yfinance e PTAX (API do Banco Central) | Pipeline diário no Kaggle com carga incremental no BigQuery. Inner join nas datas evita cruzar dias em que só um mercado operou. |
| [ETL-VAGAS-GUPY](https://github.com/AlexandreSantosRodrigues/ETL-VAGAS-GUPY) | Que ferramentas as vagas de dados pedem? | Scraping da Gupy | Selenium, pandas e Google Sheets alimentando um painel em Power BI. 12 estrelas. |
| [aws-data-pipeline](https://github.com/AlexandreSantosRodrigues/aws-data-pipeline) | Como processar CSVs automaticamente e avisar quando falham? | CSVs de teste | S3, Lambda, SQS com dead-letter queue (3 tentativas), SNS e CloudWatch, dentro do Free Tier. |
| [lakehouse-ruptura-estoque-rj](https://github.com/AlexandreSantosRodrigues/lakehouse-ruptura-estoque-rj) | Quais SKUs e fornecedores têm maior risco de ruptura? | `samples.tpch` do Databricks (dados de exemplo) | Arquitetura medalhão em SQL puro, star schema e score de risco de 0 a 100 por SKU. |
| [Supply_Chain_Weather_Impact](https://github.com/AlexandreSantosRodrigues/Supply_Chain_Weather_Impact) | O clima explica atrasos de entrega? | API Open-Meteo e 1.000 envios sintéticos | Flatten de JSON aninhado com `EXPLODE` e `ARRAYS_ZIP`, cruzado por aeroporto e data. |
| [sop-demand-forecast-dashboard](https://github.com/AlexandreSantosRodrigues/sop-demand-forecast-dashboard) ([dashboard](https://datastudio.google.com/reporting/bf13f866-7db9-4c08-86ca-528ba5f16281)) | Qual a acurácia do forecast por linha? | Fictícios: 3 linhas de lubrificantes, 24 meses | Média móvel ponderada (50/30/20), WAPE e Forecast Accuracy no Looker Studio. |
| [analise-sentimentos-google-maps](https://github.com/AlexandreSantosRodrigues/analise-sentimentos-google-maps) | Dá para classificar reviews sem treinar um modelo? | Kaggle, 1.100 reviews em inglês | TextBlob concorda com as estrelas em 69,3% dos casos. Limitação documentada: é um modelo para inglês. |

Também no GitHub: [logistics-lakehouse-analytics](https://github.com/AlexandreSantosRodrigues/logistics-lakehouse-analytics) (4 notebooks de logística com dados simulados), [databricks-cart-abandonment](https://github.com/AlexandreSantosRodrigues/databricks-cart-abandonment) (fluxo simulado de eventos com Delta Lake) e [nl-to-sql](https://github.com/AlexandreSantosRodrigues/nl-to-sql) ([demo](https://nl-to-sql-tau.vercel.app)), um tradutor de linguagem natural para SQL com Next.js e Groq.

## Ferramentas que aparecem nos repositórios

SQL (Spark SQL, BigQuery) · Python (pandas, PySpark, Selenium) · Databricks e Delta Lake · Google BigQuery · AWS (Lambda, S3, SQS, SNS) · Looker Studio · Power BI

## Contato

Aberto a conversar sobre análise de dados, SQL e automação com Python: [LinkedIn](https://www.linkedin.com/in/alexandresantosdata/).
