MVP Análise de Dados e Boas Práticas
Nome: Fabiano Humberto Duarte Barreto
Descrição do Problema
O conjunto de dados Car Sales Report consiste em registros de venda de automóveis com informações sobre os clientes, características dos automóveis, data da venda, nome da empresa revendedora e as cidades onde as vendas ocorreram (todas nos Estados Unidos). Represento uma consultoria que foi contratada por uma empresa de revenda de carros para fazer uma análise preditiva sobre o faturamento dos próximos meses das cidades onde as lojas estão localizadas. Neste contexto, será analisado o comportamento das vendas presentes no dataset para preparar um modelo de predição de faturamento mensal por cidade. Para cada cidade serão levados em consideração as seguintes características: faturamento (somatório do valor das vendas), renda anual do cliente, comportamento das vendas ao longo dos meses.

Hipóteses do Problema
As hipóteses que tracei são as seguintes:

Para cada cidade existe uma preferência do tipo de carroceria do automóvel?

Existe uma correlação entre renda anual do cliente e preço do automóvel?

Qual o faturamento médio por cidade?

Qual a marca mais vendida por cidade?

Qual cidade apresentou o maior crescimento percentual nos últimos 3 meses do período presente no dataset?

Tipo de Problema
Este é um problema supervisionado de regressão para prever o faturamento futuro por cidade, dado um conjunto de características como preço (Price ($)), loja (Dealer_Region), renda anual do cliente (Annual Income), data da venda (Date).

Seleção de Dados
O dataset Car Sales Report foi obtido através do Kaggle: https://www.kaggle.com/datasets/missionjee/car-sales-report
