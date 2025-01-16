# Projeto de Previsão de Score de Crédito

Este projeto utiliza a biblioteca scikit-learn para prever o score de crédito de clientes com base em um conjunto de dados fornecido.

## Estrutura do Projeto

- `clientes.csv`: Arquivo CSV contendo os dados dos clientes.
- `novos_clientes.csv`: Arquivo CSV contendo os dados dos novos clientes para previsão.
- `main.ipynb`: Notebook Jupyter contendo o código para análise e previsão do score de crédito.

## Descrição do Código

- O notebook começa importando os dados do arquivo [clientes.csv] e exibindo-os.
- Em seguida, verifica se há valores vazios ou em formato indevido.
- As colunas do tipo texto são transformadas em números usando `LabelEncoder`.
- Os dados são divididos em conjuntos de treino e teste.
- Dois modelos são treinados: `RandomForestClassifier` e `KNeighborsClassifier`.
- A acurácia dos modelos é avaliada e o melhor modelo é escolhido.
- O modelo escolhido é usado para fazer previsões nos dados dos novos clientes do arquivo [novos_clientes.csv].

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias.