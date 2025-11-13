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
- **Conexões em nuvem** (por exemplo, banco de dados FRED online)  
- Dados públicos adicionais (opcional)

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

### 4️⃣ Análises em DAX
Criação de medidas para:

- Crescimento de renda e renda ajustada pela inflação  
- Tendências de emprego por setor  
- Deslocamentos populacionais entre regiões  
- Correlações entre população, emprego e renda  

### 5️⃣ Criação das Visualizações
Foram usados:

- Linhas de tendência  
- Gráficos de área e barras  
- Mapas de deslocamento populacional  
- Painéis de crescimento setorial  
- Comparações entre renda e inflação  

### 6️⃣ Summary Page
A última aba do relatório contém:

- Principais insights  
- Visualizações de destaque  
- Resumo numérico das tendências  
- Conclusões estratégicas  

---

## 🔍 Tópico(s) da Análise

Você pode escolher qualquer tópico econômico.  
Este projeto explora:

> **(Preencha com seu tópico escolhido — ou análise múltipla)**

### Exemplos possíveis:
- Como os centros populacionais dos EUA estão mudando  
- Como a renda média evoluiu em relação à inflação  
- Quais setores estão crescendo ou encolhendo  
- Declínio populacional e seus impactos no mercado de trabalho  

---

## 💡 Principais Insights (Exemplo)

> *(Substitua por suas descobertas reais após finalizar o relatório.)*

- O crescimento populacional tem se deslocado para o Sul e Oeste dos EUA.  
- Renda ajustada pela inflação mostra crescimento mais lento do que a renda nominal.  
- Setores como tecnologia e saúde apresentam maior crescimento.  
- Áreas rurais demonstram declínio simultâneo de população e emprego.  

---

## 🛠 Ferramentas Utilizadas

- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
- **Excel / CSV**  
- **Conexão FRED / BLS / Census**  
- **GitHub** para versionamento  

---
📂 us-economy-analysis/
│
├── 📊 US_Economic_Indicators.pbix
├── 📁 data/
│ ├── population_data.xlsx
│ ├── employment_data.csv
│ ├── income_fred_connection.txt
│ └── additional_sources/
│
└── 📄 README.md


## 📁 Estrutura do Repositório

