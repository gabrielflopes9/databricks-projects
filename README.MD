# 🌍 Análise de Dados com API RestCountries

Este projeto simula um pipeline de ingestão e análise de dados usando Python no ambiente **Databricks Community Edition**.

---

## 🛠️ Tecnologias Utilizadas
- Python (Pandas, Requests, Plotly)
- Databricks Community Edition
- API pública: [RestCountries](https://restcountries.com/)

---

## 🔁 Pipeline Simulado (ETL)
1. **Extração**: dados via API `restcountries.com`
2. **Transformação**:
   - Tratamento de colunas aninhadas (capital, lat/lon)
   - Enriquecimento com dados de população
3. **Visualização**:
   - Mapa interativo de países
   - Análises como top 10 países mais populosos, países por continente, etc.

---

## 📊 Exemplos de Análises
- Quantidade de países por continente
- Países sem capital registrada
- População média por região
- Mapa geográfico com escala populacional (Plotly)

---

## 📁 Notebook
O notebook está disponível em:  
`notebooks/countries_etl_analysis.py`  
Ele pode ser importado diretamente no ambiente **Databricks Community Edition**.

---

## 🚀 Como Executar

1. Crie uma conta gratuita no [Databricks Community](https://community.cloud.databricks.com/)
2. Importe o notebook deste repositório
3. Execute célula por célula e acompanhe as análises no notebook

---


