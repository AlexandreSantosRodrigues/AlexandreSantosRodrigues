# Alexandre Santos

Analista de Dados com formação em Ciências Contábeis e pós-graduações concluídas em Ciência de Dados e IA e Engenharia de Computação. Conecto finanças e contabilidade à análise, automação e qualidade de dados com SQL, Python, Power BI e Databricks.

Atuo integralmente na Fundação COPPETEC (COPPE/UFRJ) desde dezembro de 2022, como profissional terceirizado pela R4 Serviços Contábeis. Desde novembro de 2025, meu foco como Analista de Dados inclui dashboards, automação e validação de informações financeiras e patrimoniais.

[Portfólio](https://portfolio-one-psi-6vlyvif38r.vercel.app) · [LinkedIn](https://www.linkedin.com/in/alexandresantosdata/)

## Projetos em destaque

### [Oil & Gas Production Lakehouse — ANP](https://github.com/AlexandreSantosRodrigues/oil-gas-production-lakehouse)

Integração de dados públicos de produção, cadastro e intervenções em poços para investigar variações de produção de petróleo.

- **Método:** Databricks, Delta Lake, camadas Bronze/Silver/Gold/Ops, modelo dimensional e rastreabilidade por SHA-256.
- **Evidência:** 315.356 registros de produção/injeção e 17.817 de intervenções publicados na Gold; 169 verificações arquivo/medida e 26 verificações de agregados aprovadas na execução documentada.
- **Explore:** [imagem pública do dashboard](https://github.com/AlexandreSantosRodrigues/oil-gas-production-lakehouse/blob/main/docs/images/dashboard-anp.png) · [notebooks exportados](https://github.com/AlexandreSantosRodrigues/oil-gas-production-lakehouse/tree/main/notebooks). Execução por notebooks, sem orquestração automática; comparações antes/depois são descritivas.

### [Fuel Price Intelligence RJ](https://github.com/AlexandreSantosRodrigues/fuel-price-intelligence-rj)

Monitoramento e previsão semanal dos preços de gasolina comum e etanol no Rio de Janeiro com dados públicos da ANP.

- **Método:** pipeline em Python, auditoria de qualidade, engenharia de características e comparação de quatro modelos com backtesting temporal.
- **Evidência:** relatórios de qualidade, métricas e previsões versionadas. O último preço conhecido apresentou o menor erro entre as abordagens avaliadas.
- **Explore:** [aplicação Streamlit](https://fuel-price-intelligence-rj.streamlit.app/) · [relatório de modelagem](https://github.com/AlexandreSantosRodrigues/fuel-price-intelligence-rj/blob/main/reports/modeling/model_report.json).

### [GA4 Multi-Touch Attribution](https://github.com/AlexandreSantosRodrigues/ga4-multi-touch-attribution)

Comparação de como diferentes regras distribuem crédito aos canais de marketing nas jornadas de compra.

- **Método:** SQL no BigQuery, auditoria de 4,3 milhões de eventos e reconstrução de sessões, compras e touchpoints.
- **Evidência:** cinco modelos — First-Click, Last-Click, Linear, Time-Decay e Position-Based — com reconciliação de conversões e receita. Atribuição não é interpretada como efeito causal.
- **Explore:** [apresentação interativa](https://alexandresantosrodrigues.github.io/ga4-multi-touch-attribution/) · [auditoria dos dados](https://github.com/AlexandreSantosRodrigues/ga4-multi-touch-attribution/blob/main/docs/01_raw_data_audit.md).

### [Superstore Sales](https://github.com/AlexandreSantosRodrigues/superstore-sales-dashboard)

Análise de vendas, margem e descontos com preparação e validação dos dados antes da visualização.

- **Método:** SQL no Databricks, camadas silver e gold, controles de qualidade e avaliação temporal de previsão com PySpark.
- **Evidência:** 9.994 itens reconciliados, decisões documentadas sobre chaves de produto e comparação entre crescimento das vendas e queda de margem.
- **Explore:** [dashboard interativo](https://alexandresantosrodrigues.github.io/superstore-sales-dashboard/dashboard/) · [qualidade e resultados](https://github.com/AlexandreSantosRodrigues/superstore-sales-dashboard/blob/main/docs/data-quality.md).

## Outros projetos selecionados

| Projeto | Problema e implementação | Evidência disponível |
|---|---|---|
| [NFLX Insight](https://github.com/AlexandreSantosRodrigues/Netflix-stock-analysis) | Pipeline Python/Colab, auditoria de preços e demonstrações da SEC, comparação de modelos e avaliação temporal. | Ridge não superou o baseline de retorno zero no teste; custos de transação alteram a comparação histórica das estratégias. |
| [AWS Data Pipeline](https://github.com/AlexandreSantosRodrigues/aws-data-pipeline) | Triagem de CSVs com Python, S3, Lambda, SQS e SNS. | Código das funções e arquivos válidos/inválidos de exemplo. |
| [Lakehouse de Ruptura](https://github.com/AlexandreSantosRodrigues/lakehouse-ruptura-estoque-rj) | Estudo de risco de abastecimento com Databricks SQL, Delta Lake e modelagem dimensional sobre TPCH. | Scripts Bronze → Silver → Gold e score heurístico; simulação, sem comprovação de ruptura real. |
| [S&OP Demand Forecast](https://github.com/AlexandreSantosRodrigues/sop-demand-forecast-dashboard) | Acompanhamento de forecast e realizado com média móvel ponderada, WAPE e acurácia em Google Sheets e Looker Studio. | Base fictícia de 24 meses e três linhas de lubrificantes; [dashboard](https://datastudio.google.com/reporting/bf13f866-7db9-4c08-86ca-528ba5f16281). |

## Habilidades técnicas

- **Linguagens:** SQL (Spark SQL e BigQuery), Python (pandas, PySpark e Selenium).
- **Plataformas e armazenamento:** Databricks, Delta Lake, Google BigQuery e AWS (S3, Lambda, SQS e SNS).
- **Análise e visualização:** Power BI, Looker Studio e Streamlit.
- **Práticas presentes nos projetos:** qualidade de dados, modelagem dimensional, reconciliação de métricas e validação temporal.
- **Versionamento e publicação:** Git/GitHub e GitHub Pages.

Os repositórios documentam fontes, premissas e limitações. Dados públicos e simulações são identificados em cada projeto; resultados projetados são separados de impactos operacionais comprovados.

## Contato

[LinkedIn](https://www.linkedin.com/in/alexandresantosdata/)

