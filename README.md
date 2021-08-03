# K-Anonimato com Generalização
O objetivo do projeto é realizar a anonimização do dataset de entrada ([Dataset_Covid_CE.csv](Dataset_Covid_CE)) usando um algoritmo de anonimização com técnica de perturbação de valores. Dois gráficos foram plotados para ajudar a identificar as diferenças entre as distribuições dos valores originais dos anonimizados.

O projeto foi realizado em python no ambiente jupyter notebook, com ajuda das bibliotecas pandas e matplotlib.

#### Funcionamento:

1. perturbação dos valores de dataNascimento através de uma função numérica que calcula uma nova data baseada na data original.
1. perturbação dos valores de municipio usando uma função utilidade que retorna outros municipios aleatórios próximos do original.