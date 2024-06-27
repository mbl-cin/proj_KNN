# Projeto de Análise de Doenças Cardíacas
Este projeto utiliza um dataset do repositório UCI Machine Learning para analisar doenças cardíacas. O objetivo é prever a presença da condição usando um modelo de classificação KNN.

Funcionalidades Implementadas:
Carregamento de Dados: Utilização do pacote ucimlrepo para importar o dataset "Heart Disease".

Pré-processamento de Dados: Normalização das features usando StandardScaler e tratamento de valores faltantes.

Treinamento do Modelo: Implementação de um classificador KNN com 3 vizinhos e avaliação da sua acurácia, precisão e recall.

Visualização de Dados: Scatterplot para explorar a relação entre as features 'Área' e 'Excentricidade' em uma plantação de arroz, diferenciando por tipo.

Otimização de Parâmetros: Utilização de validação cruzada para encontrar o melhor número de vizinhos (K) no modelo KNN.

Tecnologias Utilizadas:
Python, Pandas, NumPy para manipulação e análise de dados.
Scikit-learn para aprendizado de máquina e métricas de avaliação.
Seaborn e Matplotlib para visualização de dados.
