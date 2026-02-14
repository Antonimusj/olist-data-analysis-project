🗄️ Construção de Base Analítica e Pipeline de Dados – E-commerce (Olist Dataset)

Este projeto tem como foco a construção de uma base analítica estruturada a partir de dados transacionais do e-commerce brasileiro Olist.

O objetivo principal foi desenvolver um fluxo completo de extração, transformação e modelagem de dados (ETL), consolidando múltiplas tabelas relacionais em uma base preparada para consumo analítico e visualização.

## Estrutura do Projeto

```bash
/sql        → Scripts de modelagem e consolidação
/notebooks  → Transformações e análises em Python
/dashboard  → Arquivo Power BI (.pbix)
/data       → Dados intermediários
```

🧱 Arquitetura do Projeto

O pipeline foi desenvolvido em três etapas principais:

🔹 Fase 1 – SQL (Modelagem e Consolidação)

Extração de dados brutos

JOINs entre múltiplas tabelas relacionais

Tratamento de inconsistências

Criação de base consolidada para análise

Modelagem relacional e persistência em MySQL / SQLite.

Foco: construção de dataset limpo e estruturado.

🔹 Fase 2 – Python (Transformação e Feature Engineering)

Manipulação de dados com Pandas

Tratamento de valores ausentes

Padronização de variáveis

Criação de métricas derivadas a partir de agregações temporais e consolidação transacional (recorrência, AOV, LTV).

Preparação da base para visualização

Foco: transformação e enriquecimento da base analítica.

🔹 Fase 3 – Camada Analítica (Power BI)

Conexão com base estruturada

Construção de dashboard interativo

Organização de indicadores derivados da base transformada
🖥️ Visualização do Dashboard Final
![Dashboard Final de Rendimento](dashboard_final.jpg)

📊 Resultados Técnicos

A estrutura final permitiu:

Cálculo de métricas de recorrência

Segmentação por região

Análise de comportamento de parcelamento

Estruturação de indicadores como AOV e LTV

Exemplo de análise derivada da base estruturada:
![Comportamento de Vendas](analise_comportamento_vendas.png)

🛠️ Tecnologias Utilizadas

SQL (MySQL / SQLite)
Modelagem relacional, JOINs, consolidação e estruturação de base analítica.

Python (Pandas, Seaborn, Matplotlib)
Processo de transformação, limpeza e feature engineering.

Power BI
Camada de consumo analítico e visualização.

Jupyter Notebook
Documentação técnica do processo de transformação.

🎯 Objetivo do Projeto

Este estudo foi desenvolvido como exercício prático de Engenharia de Dados aplicada, com foco em:

Construção de pipeline

Integração de múltiplas fontes

Estruturação para consumo analítico

Organização de base relacional

👤 Autor

José Antônio da Silva Estudante de Ciência de Dados (3º Semestre) na Faculdade Descomplica.





---



---

### 🤝 Conecte-se comigo
Para discussões sobre Engenharia de Dados, parcerias em projetos de Sports Analytics ou oportunidades profissionais:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jose-antonio-da-silva-ds)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/antonimusarch)

---



