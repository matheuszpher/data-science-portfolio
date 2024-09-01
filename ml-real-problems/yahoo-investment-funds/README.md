# 🚧 EM CONTRUÇÃO 🚧
# Análise e Avaliação da Liquidez dos ETFs

## Introdução

Este projeto visa analisar e avaliar a liquidez dos ETFs (Exchange-Traded Funds) utilizando dados financeiros disponíveis, como o valor total dos ativos (`total_net_assets`). Embora não tenhamos dados diretos sobre o spread, que é uma medida tradicional de liquidez, utilizaremos outras variáveis para inferir a liquidez dos ETFs e entender melhor sua eficiência no mercado.

## Contexto dos ETFs

### O que são ETFs?

**Exchange-Traded Funds (ETFs)** são fundos de investimento que são negociados em bolsas de valores, semelhantes às ações. Eles são projetados para replicar o desempenho de índices de mercado, setores ou ativos específicos, oferecendo uma maneira acessível de diversificação de investimentos.

### Importância da liquidez

A **liquidez** de um ETF refere-se à facilidade com que ele pode ser comprado ou vendido no mercado sem causar grandes mudanças em seu preço. A liquidez é crucial para investidores, pois afeta o custo de transação e a capacidade de executar ordens de forma eficiente.

## Desafios e Dados Disponíveis

### Desafios

- **Falta de dados de Spread:** O spread, que é a diferença entre o preço de compra e o preço de venda, é um indicador direto de liquidez. No entanto, não temos essa informação disponível.

### Dados disponíveis

- **`fund_symbol`:** O símbolo do ETF.
- **`total_net_assets`:** Valor total dos ativos líquidos que um ETF possui.
- **`fund_yield_std`:** Desvio padrão do rendimento do fundo, indicando a volatilidade do rendimento.
- **`fund_category_freq_std`:** Desvio padrão da frequência da categoria do fundo, refletindo a variabilidade na categorização.
- **`fund_return_ytd_std`:** Desvio padrão do retorno do fundo no ano até a data.
- **`day50_moving_average_std`:** Desvio padrão da média móvel de 50 dias do preço do fundo.
- **`week52_high_std`:** Desvio padrão da alta do preço das últimas 52 semanas.
- **`week52_low_std`:** Desvio padrão da baixa do preço das últimas 52 semanas.
- **`fund_price_earning_ratio_std`:** Desvio padrão da relação preço/lucro do fundo.
- **`open_std`:** Desvio padrão do preço de abertura do ETF.
- **`high_std`:** Desvio padrão do preço mais alto do ETF.
- **`low_std`:** Desvio padrão do preço mais baixo do ETF.
- **`close_std`:** Desvio padrão do preço de fechamento do ETF.
- **`volume_std`:** Desvio padrão do volume de negociação do ETF.



- [Yahoo Finance](https://finance.yahoo.com)
- Documentação das ferramentas e bibliotecas utilizadas no projeto.

