# Suelen_Tonello_Analise_Varejo_T8

# Sobre o projeto

A partir de uma base de dados Varejo, foi realizada a leitura, limpeza, tratamento e análise dos dados.

1. A base inicial continha 830000 linhas e 14 colunas. Foram removidas 4 colunas pois seus valores eram nulos.

2. As colunas foram renomeadas para maior compreensão.

3. Tratados os valores nulos, inconsistências textuais e diferenças na escrita.

4. Verificados valores ausentes nas colunas `categoria` e `nome_produto`. Os mesmos não foram excluídos pois poderiam impactar o restante das análises.

5. Encontradas 96553 duplicatas excedentes que não foram excluídas por se tratar de compras de mesmo cliente.

6. Dentre os 1000 clientes distintos, 473 possuem ao menos um filho. O Maior número de filhos encontado foi quatro. O menor número de filhos foi encontrado em solteiros e viúvos. O segmento com maior número de filhos foi o "B".

**Recomendação**
Verificar as ausências de valores nas colunas `categoria` e `nome_produto`, para que tenhamos uma análise completa dos dados.

**Limitação**
Pela falta de dados nas colunas `categoria` e `nome_produto`, houve uma limitaçao de análise mais aprofundada e completa desta base.

Base de dados (varejo) Kaggle: https://www.kaggle.com/datasets/namespaiva/base-varejo/data

Utilizado o GoogleColab para realizar o projeto. 
