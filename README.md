
# 📊 Dashboard DRE - Power BI

Este projeto consiste em um **Dashboard Interativo de Demonstração de Resultados do Exercício (DRE)** desenvolvido no **Power BI**, com foco nas análises **vertical** e **horizontal** de resultados financeiros. O objetivo é oferecer uma visualização clara e estratégica dos indicadores econômicos da empresa, permitindo análise comparativa entre metas, realizados e históricos.

## 🧾 Sobre o Dashboard

O Dashboard é dividido em três abas principais:

### 1. **Homepage**
Página inicial com uma interface amigável e botões de navegação destacados para:
- **Análise Vertical**
- **Análise Horizontal**

Essa tela apresenta o título “Demonstrativo de Resultados do Exercício (DRE)” com um design corporativo e moderno, facilitando o uso para apresentações e navegação executiva.

---

### 2. **Análise Vertical (Real vs Meta)**

Nesta aba, são apresentados comparativos entre os valores realizados e as metas orçamentárias. A estrutura segue o padrão da DRE com indicadores como:

- Receita Operacional Bruta
- Deduções da Receita
- Receita Líquida
- Custos e Despesas Operacionais
- EBITDA
- Resultado Financeiro
- Resultado Líquido do Exercício

Recursos visuais:
- Tabelas com indicadores de KPI e variações (%)
- Indicadores com setas de tendência (↑ ↓)
- Gráficos de barras com análise de desempenho mensal
- Destaque do melhor mês e avaliação de metas batidas ao longo dos meses

---

### 3. **Análise Horizontal (Evolução por Ano)**

Essa aba permite a análise da evolução dos resultados ao longo dos anos (2021, 2022 e 2023), ideal para identificar tendências e sazonalidades.

Principais recursos:
- Comparação ano a ano (% AH)
- Identificação visual de crescimento ou queda por KPI
- Gráficos comparativos de resultado líquido acumulado
- Destaque do pior mês em comparação ao previsto

---

## 🔍 Filtros Dinâmicos

Todos os relatórios contam com filtros laterais que permitem segmentar os dados por:

- Ano
- Mês
- Filial
- Meta (Orçado ou Previsto)

Esses filtros são interativos e atualizam todas as visualizações em tempo real conforme a seleção.

---

## 📅 Tabelas Utilizadas

Entre as principais tabelas que compõem o modelo de dados do projeto, destacam-se:

- `dCalendario`: Tabela de calendário para controle temporal
- `fLançamentos`: Fatos financeiros lançados
- `dPlanoConta`: Estrutura contábil utilizada na DRE
- `dFilial`, `centro_de_custo`, `categoria`, entre outras dimensões
- `auxMeta`, `#Previsao`, `#Orcamento`: Metas e previsões

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Power Query (ETL)
- Modelagem Estrela
- Visualizações nativas do Power BI

---

## 📸 Screenshots

### 🖥️ Homepage
![Homepage](./Captura%20de%20tela%202025-07-16%20150103.png)

### 📈 Análise Vertical (Real vs Meta)
![Análise Vertical](./Captura%20de%20tela%202025-07-16%20150113.png)

### 📉 Análise Horizontal (Evolução Anual)
![Análise Horizontal](./Captura%20de%20tela%202025-07-16%20150120.png)

---

## 💡 Objetivos do Projeto

- Facilitar o acompanhamento da performance financeira.
- Auxiliar a diretoria em decisões estratégicas baseadas em dados.
- Centralizar a análise de metas, variações e tendências de forma visual.

---

## 📬 Contato

Caso tenha interesse em saber mais ou implementar algo semelhante, entre em contato com o responsável pelo projeto:

**Giulliano Veiga Ferreira Filho**  
📧 [Inserir e-mail de contato]  
🏢 [Nome da empresa ou equipe, se aplicável]
