# Capítulo 1
## Básico sobre DataFrame do Pandas

Pandas é uma biblioteca Python de código aberto para análise de dados, permintindo à linguagem Python:
* trabalhar com dados do tipo tabela;
* carregar, manipular, alinhar e combinar dados rapidamente.

O Pandas introduz dois tipos novos de dados:
* `DataFrame`: representa dados de planilha ou retangulares;
* `Series`: corresponde a uma coluna de uma `DataFrame`.

## Códigos usados

Comando               |Descrição
---                   |---
`import pandas as pd` | Comando Python para importação da biblioteca Pandas
`pd.read_csv()`       | Carregando um arquivo `csv` na memória
`df.head()`           | Exibe as 5 primeiras linhas do `DataFrame`
`df.shape`            | Atributo de um `DataFrame`, apresenta uma tupla da forma (número de linhas, número de colunas) da tabela
`df.columns` | Obtém o nome das colunas
`df.dtypes`  | Obtém o tipo de cada coluna
`df.info()`  | Informações mais completas sobre o dataframe

## Tipos de dados em Python e em Pandas

Tipo do Pandas | Tipo do Python | Descrição
---            | ---            | ---
`object`| `string` | Tipo de dado mais comum: cadeia de carácteres
`int64`| `int` | Números inteiros
`float64`| `float` | Números com decimais
`datetime64`| `datetime` | Representam datas, não é carregado por padrão em Python, mas fazem parte de sua biblioteca padrão, precisando ser carregados




