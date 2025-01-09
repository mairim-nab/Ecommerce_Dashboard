# Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

Este projeto foi elaborado com base em um dataset que reúne informações de vendas de uma empresa com diversas lojas localizadas na região Sudeste, no estado da Bahia e no Paraná. A modelagem de dados foi realizada dentro do Power BI utilizando as linguagens M e DAX, permitindo a transformação e análise dos dados. Exemplos de modelagem aplicados:

- Criação de uma coluna de margem de lucro com a seguinte fórmula DAX:
  ```
  margem_de_lucro = 1 - (DIVIDE([Preço Custo], [Valor de Venda], 0))
  ```
  Essa coluna foi explorada no relatório final para identificar a rentabilidade dos produtos.

- Desenvolvimento de uma medida para calcular a média de vendas:
  ```
  Media_vendas = AVERAGE(Custos[Valor de Venda])
  ```
  Essa métrica foi utilizada como um dos indicadores principais no dashboard.

## Conclusões

O projeto tinha como objetivo atender às seguintes demandas de negócios: 
- Cálculo da média de vendas.
- Análise da margem de lucro.
- Comparação entre valor de venda e preço de custo dos produtos.
- Visualização de um indicador chave de desempenho (meta de margem de lucro).

O relatório final respondeu claramente a todas essas demandas, fornecendo ao setor de negócios uma ferramenta prática para análises futuras relacionadas a vendas e custos.

## Insights Gerados

- **Gráfico de média de vendas (março):**
  Um gráfico de linhas foi utilizado para representar as vendas do mês de março. A análise revelou uma oscilação significativa ao longo do período, com um pico entre os dias 5 e 10.

- **Gráfico de margem de lucro por produto:**
  A visualização demonstrou que o produto com maior volume de vendas foi o de código BX103. Essa informação pode direcionar estratégias para aumentar a oferta e promoção desse item.

- **Gráfico de dispersão (valor de vendas x preço de custo):**
  A análise mostrou uma correlação positiva entre preço de custo e valor de venda, evidenciando uma relação clara e consistente entre essas variáveis.

- **Meta da margem de lucro:**
  A análise revelou que as vendas estão 4,72% abaixo da meta estabelecida, que é de 53,01%. Esse dado foi apresentado de forma clara para facilitar a tomada de decisões.

Com essas informações, o dashboard não apenas atendeu às demandas do problema de negócio, mas também forneceu insights valiosos para estratégias futuras da empresa.
