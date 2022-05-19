# Análise dos Preços de Soja
Análise das médias de preços anuais de soja praticado no porto de Paranaguá - PR.

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=BLUE&style=for-the-badge)

O objetivo dessa análise é entender a dinâmica dos preços (R$) de venda da saca de soja (60 kg), trabalhando com valores médios de preços por ano.

A base de dados foi adquirida de forma gratuita através do CEPEA - Centro de Estudos Avançados em Economia Aplicada.

## Técnicas e tecnologias utilizadas

- ``Python``
- ``Jupyter Notebook``
- ``Estatística``

## Links importantes

[Base de Dados](https://www.cepea.esalq.usp.br/br/indicador/soja.aspx)

- Fonte: CEPEA - Centro de Estudos Avançados em Economia Aplicada.

- Valores em Reais para saca de 60 kg.

[Cultura da Soja](https://www.embrapa.br/web/portal/soja/cultivos/soja1/historia)

- A cultura da soja tem enorme importância econômica para o Brasil, tendo o ano de 2021 como referência a soja foi o produto mais exportado pelo país o que colocou o Brasil em 1º lugar no ranking mundial de produtores da leguminosa, com a venda de 85,6 milhões de toneladas para fora do país.

## Tratamento dos Dados

- Após a aquisição dos dados, foi realizado a formatação dos dados núméricos em float64;

- Não foram identificados valores nulos na base de dados nem outliers;

- Foi realizado o agrupamento dos preços por ano e retirado uma média;

- geração do gráfico de barra para visualição dos dados.

