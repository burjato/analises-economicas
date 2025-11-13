# 📈 Análise de Indicadores Econômicos dos EUA – Modelo de Dados & Dashboard em Power BI

## 🏛️ Visão Geral do Projeto

Este projeto foi desenvolvido para uma **empresa de pesquisa econômica** interessada em compreender melhor como os principais componentes da **economia dos Estados Unidos** estão evoluindo ao longo do tempo.  
A análise foca em tendências de **população, emprego e renda**, utilizando fontes oficiais como:

- **US Bureau of Labor Statistics (BLS)**
- **US Census Bureau**
- **US Federal Reserve (FRED)**

O projeto envolve a criação de um **robusto modelo de dados no Power BI**, integrando múltiplas fontes e formatos, seguido da construção de um relatório com visualizações, cálculos em DAX e técnicas de análise quantitativa.

---

## 🎯 Objetivos do Projeto

1. **Coletar dados históricos e atuais** de várias fontes governamentais confiáveis.  
2. **Limpar, transformar e integrar datasets** em um modelo de dados unificado.  
3. **Criar relacionamentos** entre tabelas de população, emprego e renda.  
4. **Realizar análises quantitativas** usando DAX e recursos avançados do Power BI.  
5. **Construir um relatório interativo** que explora insights da economia dos EUA.  
6. **Resumir as descobertas-chave** em uma aba final de resumo.

---

## 🗂 Fontes de Dados

As análises foram baseadas em dados disponibilizados em diferentes formatos:

- **Planilhas (Excel/CSV)**  
- **Conexões em nuvem**

Os dados incluem:

- Mudanças populacionais por região e ano  
- Estatísticas de emprego e tendências setoriais  
- Níveis de renda comparados à inflação  
- Indicadores gerais de crescimento econômico  

---

## 🧩 Processo de Modelagem de Dados

As seguintes etapas foram realizadas para construir o modelo no Power BI:

### 1️⃣ Obtenção & Conexão aos Dados
- Download e armazenamento de arquivos locais.  
- Coleta das credenciais e URLs para conexões em nuvem (como FRED).  

### 2️⃣ Limpeza de Dados (Power Query)
- Remoção de nulos e duplicatas  
- Padronização de nomes e formatos de colunas  
- Correção de formatos de data  
- Ajustes para garantir granularidade consistente  

### 3️⃣ Criação do Modelo de Dados
- Carregamento das tabelas  
- Estabelecimento de **relacionamentos estruturados**  
- Construção de um esquema eficiente (estrela ou floco de neve)  

### 4️⃣ Criação das Visualizações
Foram usados:

- Linhas de tendência  
- Gráficos de barras  
- Painéis de emprego setorial    

### 5️⃣ Summary Page
A última aba do relatório contém:

- Principais insights  
- Visualizações de destaque    

## 🛠 Ferramentas Utilizadas

- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
- **Excel / CSV**  
- **Conexão FRED / BLS / Census**  
- **GitHub** para versionamento  

---
📂 analises-economicas/
│
├── 📊 population statistics data model.pbix
│ ├── BLS - Avg Hours Per Day Sleeping.csv
│ ├── BLS - Avg Hours Per Day Socializing and Communicating.csv
│ ├── BLS - Avg Hours Per Day Watching TV.csv
│ ├── BLS - Unemployment Rate.csv
│ ├── Historical Population.xlsx
│ └── Industry Earnings.xlsx
│
└── 📄 README.md


