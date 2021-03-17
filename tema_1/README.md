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
- A normalização de Min-Máx visa manter os valores do seu dataset entre 0,0 e 1,0 ou -1,0 e 1,0.

- Abaixo temos a imagem que mostra como é calculada a normalização Min-Max:

![1](https://github.com/BrunoXirrato/Projeto-Estudando-Ci-ncia-de-Dados/blob/main/tema_1/1.png)

- X é o valor inicial do vetor, Xmin é o menor valor deste vetor, Xmax é o valor Máximo do vetor e Xchanged é o valor X normalizado.​

### Standard <h3>

- A padronização de dados Standard, mais conhecida como Z-score, tem o mesmo princípio do Min-Max. É utilizado da mesma maneira que o Min-Máx, tentando sempre manter o desvio padrão dos dados mais próxima de 1.

- Abaixo temos a imagem que mostra como é calculada a normalização Min-Max:

(Colocar IMG)

- X é o valor inicial do vetor, “mih” é a media deste vetor e “roh” o desvio padrão

### QuantileTransformer

- A padronização de dados QuantileTransformer tem uma vantagem muito grande em cima das outras normalizações por lidar bem com outliers. 

- O conceito matemático de QuantileTransformer é o seguinte:

(COLOCAR IMG)

- X é o valor inicial do vetor,u é a media deste vetor e Q2 é o segundo quartil.
