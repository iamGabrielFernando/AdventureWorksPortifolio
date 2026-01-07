# Sales Overview Dashboard – Power BI

## Contexto do Projeto
Este projeto foi desenvolvido com o objetivo de consolidar dados de vendas e fornecer uma visão analítica do desempenho financeiro da empresa, permitindo avaliar receita, custo e margem sob diferentes perspectivas (linha de negócio, região e planta).

O foco principal não foi o aspecto visual, mas sim a **estrutura analítica, a modelagem de dados e a lógica por trás das decisões de negócio**.

---

## Problema de Negócio
Antes do desenvolvimento do dashboard, as informações de vendas não permitiam:
- Visualizar a concentração de receita por linha de negócio
- Comparar o desempenho entre regiões e plantas
- Avaliar a rentabilidade de forma objetiva
- Identificar tendências ao longo do tempo

---

## Objetivos Analíticos
O dashboard foi estruturado para responder às seguintes perguntas:
- Qual linha de negócio representa a maior parcela da receita?
- Quais divisões regionais concentram o faturamento?
- Como as vendas evoluem mensalmente?
- Qual é a contribuição de cada planta para o resultado total?

---

## Modelagem de Dados
Foi adotada uma modelagem em formato estrela, composta por:
- Tabela fato de vendas (receita e custo)
- Dimensões de data, linha de negócio, divisão e planta

Essa abordagem facilita a escalabilidade do modelo e a criação de medidas DAX reutilizáveis.

---

## Estratégia de Medidas (DAX)
As métricas foram construídas de forma incremental:
- Medidas base para receita e custo
- Medidas derivadas para margem e margem percentual
- Uso de medidas em vez de colunas calculadas, priorizando desempenho e flexibilidade

---

## Decisões de Visualização
Cada visual foi escolhido com base no tipo de análise desejada:
- Gráficos de barras para comparação entre categorias
- Gráficos de linha para análise de tendência temporal
- KPIs para leitura rápida de indicadores financeiros

Elementos puramente decorativos foram evitados para priorizar clareza analítica.

---

## Limitações do Projeto
- Base de dados simplificada, sem detalhamento por cliente ou produto
- Ausência de metas históricas para comparação de desempenho
- Projeto desenvolvido com foco analítico e demonstrativo

---

## Possíveis Evoluções
- Análise de crescimento (YoY / MoM)
- Avaliação de margem por produto ou cliente
- Integração com banco de dados SQL
- Automatização de atualização dos dados

---

## Autor
Gabriel Fernando  
Engenharia de Produção | Análise de Dados | Power BI
