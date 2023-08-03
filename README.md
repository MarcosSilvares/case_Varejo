# Case de Varejo

## Contextualizando:

Uma loja de varejo deseja criar algumas métricas para acompanhar seus resultados, eles possuem duas bases: Base Cliente e Base Vendas.

A missão é fazer todo o tratamento e união das bases para a construção de algumas métricas.

> Métricas:

Departamentos mais vendidos:
Análise dos dados de vendas para identificar os departamentos que obtiveram maior volume de vendas. Essa métrica auxilia na compreensão dos setores mais populares e pode guiar decisões estratégicas.

Média de Preço com frete por Nome de Departamento:
Cálculo da média de preço total, considerando o valor do frete, para cada departamento específico. Essa análise oferece insights sobre padrões de preço e despesas por departamento.

Quantidade de vendas por Mês:
Visualização da quantidade de vendas realizadas em cada mês, permitindo a identificação de padrões sazonais e tendências de demanda.

Média de renda para cada tipo de canal de venda:
Cálculo da média de renda gerada por cada canal de venda utilizado pela empresa, permitindo uma compreensão do desempenho de cada canal.

Média de idade de clientes por bandeira:
Cálculo da média de idade dos clientes para cada bandeira de cartão de crédito utilizada nas transações, fornecendo informações sobre preferências de pagamento e segmentação de clientes.

> Premissas:

Antes de iniciar a analise e a criação das métricas é importante ter em mente algumas premissas do negocio que foram expostas pela Varejista. A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações sobre sua Unidade Federativa(UF). Para solucionar este problema, foi orientado que as compras que não apresentam a UF fossem consideradas como pertencentes ao estado do Mato Grosso do Sul(MS). A segunda premissa é que o preço de um produto(descrito no dataset como "Preço") não pode ser maior do que o preço do produto + frete(descrito no dataset como "Preço_com_frete").








