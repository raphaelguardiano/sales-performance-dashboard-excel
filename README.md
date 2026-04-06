# 📊 Sales Performance Dashboard — Excel

Este é meu primeiro projeto de portfólio em análise de dados.

O objetivo foi transformar dados brutos de vendas em um dashboard executivo e, a partir dele, gerar análises que apoiem a tomada de decisão.

---

# 📌 Contexto de Negócio

Empresas que operam com grande volume de vendas precisam acompanhar constantemente seus indicadores para entender:

- como está o desempenho geral
- quais categorias geram mais valor
- onde existem distorções entre faturamento e lucro

Sem essa visibilidade, a tomada de decisão tende a ser reativa e pouco eficiente.

---

## 🎯 Problema de Negócio

Empresas que utilizam dados de vendas no Excel frequentemente possuem visibilidade sobre volume de vendas, mas não sobre a real lucratividade do negócio.

Isso dificulta identificar quais categorias e produtos realmente geram resultado financeiro positivo, podendo levar a decisões baseadas apenas em receita e não em eficiência.

Este projeto foi desenvolvido para resolver essa lacuna, analisando a relação entre receita e lucro para identificar distorções de rentabilidade.

---

# 🎯 Pergunta de Análise

Como está a performance de vendas da empresa e quais fatores realmente influenciam o resultado financeiro?

---

## 🧪 Hipóteses de Análise

Antes da análise, foram consideradas as seguintes hipóteses com base no problema de negócio:

- Algumas categorias apresentam alto volume de vendas, mas baixa eficiência financeira.  
- A lucratividade do negócio não está distribuída proporcionalmente à receita.  
- Existem categorias com maior capacidade de geração de lucro que podem ser priorizadas.  

Essas hipóteses orientaram a análise e ajudaram a direcionar a investigação dos dados para identificar distorções entre receita e lucratividade.

---

# 🗂️ Dataset Utilizado

Fonte: Kaggle  
Arquivo: Sample - Superstore.csv

Principais campos:

- Order Date
- Region
- Category
- Sub-Category
- Product Name
- Sales (receita)
- Profit (lucro)
- Quantity
- Discount

---

# ⚙️ Metodologia

O projeto foi estruturado em etapas:

1. Importação e organização dos dados  
2. Limpeza e padronização da base  
3. Criação de métricas (KPIs)  
4. Construção de tabelas dinâmicas  
5. Desenvolvimento do dashboard  
6. Análise exploratória e diagnóstica  

---

# 📈 KPIs Monitorados

| KPI                  | Descrição                         |
|----------------------|----------------------------------|
| Receita Total        | Soma total das vendas            |
| Lucro Total          | Soma total do lucro              |
| Número de Pedidos    | Total de pedidos realizados      |
| Quantidade Vendida   | Total de itens vendidos          |
| Ticket Médio         | Receita média por pedido         |
| Margem de Lucro      | Percentual de lucro sobre vendas |

---

# 📊 Dashboard

## Visão Geral
![Dashboard](images/dashboard_overview.png)

## KPIs
![KPIs](images/kpis.png)

## Vendas ao longo do tempo
![Vendas ao longo do tempo](images/sales_trend.png)

## Vendas por região
![Vendas por região](images/sales_region.png)

## Vendas por categoria
![Vendas por categoria](images/sales_category.png)

## Top produtos
![Top produtos](images/top_products.png)

---

# 🔍 Análises Realizadas

Além da construção do dashboard, foram realizadas análises adicionais para entender melhor o desempenho do negócio:

- Análise de margem por categoria (eficiência)
- Comparação entre receita e lucro
- Participação percentual por categoria
- Análise de concentração (Pareto) por subcategoria

---

# 🔍 Principais Insights

A análise revelou padrões relevantes para o negócio:

- A categoria **Technology** apresenta alta eficiência, concentrando **36% da receita e 51% do lucro**, sendo a principal responsável pelo resultado financeiro.

- A categoria **Office Supplies** apresenta desempenho consistente, com equilíbrio entre receita e lucratividade.

- A categoria **Furniture**, apesar de representar cerca de **32% da receita**, contribui com apenas **6% do lucro**, indicando **baixa eficiência econômica**.

- Existe um **desbalanceamento entre volume e rentabilidade**, onde parte relevante do faturamento não se converte em lucro.

- A análise de Pareto mostrou que aproximadamente **50% das subcategorias geram mais de 80% da receita**, indicando uma concentração moderada.
 
## 💡 Insight-chave de Negócio

Apesar da categoria Furniture representar uma parcela relevante da receita, sua contribuição para o lucro é significativamente baixa.

Isso indica que o crescimento dessa categoria não necessariamente gera valor para o negócio, evidenciando um problema de margem que pode impactar diretamente a rentabilidade geral.

---

## 📌 Recomendações de Negócio

### 1. Revisar estratégia da categoria Furniture

A categoria Furniture apresenta alta participação na receita, mas baixa contribuição no lucro. Isso indica que vender mais nessa categoria não necessariamente melhora o resultado do negócio.

**Ação recomendada:** reavaliar preços, descontos e estratégia comercial da categoria.  
**Justificativa baseada nos dados:** alta receita com baixa lucratividade.  
**Impacto esperado no negócio:** aumento da margem geral sem depender de aumento no volume de vendas.

---

### 2. Priorizar expansão da categoria Technology

A categoria Technology se destacou tanto em receita quanto em lucro, demonstrando maior eficiência financeira em comparação com as demais.

**Ação recomendada:** priorizar ações comerciais e estratégicas voltadas para essa categoria.  
**Justificativa baseada nos dados:** alta participação em receita e forte contribuição para o lucro.  
**Impacto esperado no negócio:** crescimento mais sustentável, com melhor retorno financeiro.

---

### 3. Reavaliar o mix de produtos dentro de Furniture

O baixo retorno da categoria sugere que parte dos produtos pode estar comprometendo a rentabilidade.

**Ação recomendada:** revisar o mix de produtos e identificar itens com baixa eficiência financeira.  
**Justificativa baseada nos dados:** a categoria gera receita, mas não converte isso em lucro na mesma proporção.  
**Impacto esperado no negócio:** melhoria da eficiência da categoria e redução de distorções de rentabilidade.

---

# 💡 Possíveis Ações de Negócio

Com base nos insights obtidos, algumas ações estratégicas poderiam ser consideradas:

- Revisar a estratégia da categoria **Furniture**, avaliando preços, descontos e custos.

- Priorizar investimentos em categorias mais eficientes, como **Technology**.

- Monitorar subcategorias com alto volume de vendas, mas baixa contribuição para o lucro.

- Buscar equilíbrio entre crescimento de receita e geração de valor.

---

# 🧠 Aprendizados

Durante o desenvolvimento deste projeto, foram trabalhados conceitos como:

- estruturação de problemas de negócio  
- análise de eficiência (margem)  
- comparação entre métricas  
- análise de concentração (Pareto)  
- uso de Excel para análise de dados  

---

## 📌 Conclusão

Este projeto demonstra como dados podem ser utilizados não apenas para visualizar resultados, mas para orientar decisões estratégicas de negócio, identificando onde o crescimento realmente gera valor.

A análise evidenciou que categorias com alto volume de vendas nem sempre contribuem proporcionalmente para o lucro, reforçando a importância de avaliar eficiência e não apenas faturamento.

---

## 💼 Aplicação como Serviço

Este projeto pode ser aplicado como um serviço de análise de vendas e lucratividade para empresas que utilizam Excel no dia a dia.

### Para quem é
- Pequenas e médias empresas  
- E-commerces  
- Negócios que utilizam planilhas para controle de vendas  

### Problema que resolve
- Falta de clareza sobre quais produtos ou categorias realmente geram lucro  
- Decisões baseadas apenas em volume de vendas  
- Dificuldade em identificar distorções de rentabilidade  

### Tipo de entrega
- Dashboard de vendas em Excel  
- Análise de lucratividade por categoria e produto  
- Identificação de oportunidades de melhoria  
- Recomendações práticas para tomada de decisão  

---

# 📎 Sobre o Projeto

Este projeto faz parte da minha transição de carreira para a área de análise de dados.

Estou desenvolvendo projetos práticos com foco em:

- análise de dados  
- construção de dashboards  
- geração de insights de negócio  