# Dashboard de Vendas, Custo, Margem de Lucro e KPI

Este projeto foi desenvolvido como parte do meu aprendizado prático no curso **Microsoft Power BI Para Business Intelligence e Data Science** da **Data Science Academy (DSA)**. O objetivo foi aplicar conceitos técnicos avançados para transformar dados operacionais e financeiros em inteligência visual, permitindo que tomadores de decisão analisem a saúde financeira da empresa a partir do cruzamento de vendas, custos logísticos e lucratividade real.

## Visualização do Dashboard
*dash02.png*

---

## Objetivos de Negócio (Perguntas Respondidas)

O painel foi modelado estrategicamente para responder a perguntas de negócio essenciais sobre performance, metas e eficiência de custos:

* **Pergunta 1: Qual foi o total de valor de venda considerando cada modo de envio dos pedidos?**
  * *Solução Visual:* Utilização de um **Gráfico de Cascata (Waterfall Chart)** para demonstrar o impacto acumulado de cada modalidade de envio (Classe Padrão, Segunda Classe, Primeira Classe e Mesmo Dia) na composição do faturamento total da companhia.
* **Pergunta 2: Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?**
  * *Solução Visual:* Implementação de um **Treemap**, permitindo identificar de forma hierárquica e proporcional que os mercados APAC e US lideram as médias de despesas logísticas.
* **Pergunta 3: A empresa atingiu sua meta de vendas para o período analisado?**
  * *Solução Visual:* Criação de um indicador de **Medidor (Gauge KPI)** calibrado com a meta estipulada de **350** para o valor médio de venda mensal. O recurso visual responde instantaneamente se o indicador de desempenho ficou acima ou abaixo das expectativas do negócio em meses específicos (como Abril de 2014) através da segmentação temporal.
* **Pergunta 4: Qual categoria de produto apresentou o maior lucro médio?**
  * *Solução Visual:* Construção de um **Gráfico de Rosca (Donut Chart)** para detalhar a distribuição do lucro (calculado na raiz através da lógica: *Valor da Venda - Custo de Envio*), destacando a performance das categorias de Tecnologia, Móveis e Materiais de Escritório.
* **Pergunta 5: Qual foi o comportamento da margem de lucro ao longo do tempo?**
  * *Solução Visual:* Desenvolvimento de um **Gráfico de Linhas** temporal e granular, mapeando a evolução histórica da margem de lucro (razão entre o Lucro Líquido e o Valor da Venda) por Ano, Trimestre, Mês e Dia, facilitando a identificação de sazonalidades ou quedas abruptas de rentabilidade.

---
