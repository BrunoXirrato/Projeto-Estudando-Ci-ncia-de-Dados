# **Projeto: Estudando Ciência de Dados**

# **Tema 1: Normalização e Padronização de Dados**

- **O que é:** É um pré processamento das variáveis com o intuito de manter todos os valores de um vetor em uma mesma escala.
- **Quando utilizar:** Quando temos muitos valores outliers ou uma grande variação nos valores do dataset.

## Tipos de normalização e padronização <h2>

Temos diversos tipos de bibliotecas do Python que são utilizadas para normalizar dados.  Aqui estão alguns exemplos:

- StardardScaler
- Normalizer
- Min-Max
- Standard(ou Z-test)
- Quantile Transformer
- etc

Nesta arquivo irei explicar com mais detalhes os conceitos Min-Max, Standard e Quantile Transformer.

### Min-Max <h3>
A normalização de Min-Máx visa manter os valores do seu dataset entre 0,0 e 1,0 ou -1,0 e 1,0.

Abaixo temos a imagem que mostra como é calculada a normalização:

(Colocar IMG)

X é o valor inicial do vetor, Xmin é o menor valor deste vetor, Xmax é o valor Máximo do vetor e Xchanged é o valor X normalizado.​

### Standard <h3>

X é o valor inicial do vetor, “mih” é a media deste vetor e “roh” o desvio padrão

### QuantileTransformer

X é o valor inicial do vetor,u é a media deste vetor e Q2 é o segundo quartil.
