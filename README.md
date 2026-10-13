Projeto de IA para Análise Preditiva

1. Objetivo

Este projeto tem como objetivo desenvolver modelos de Inteligência Artificial para prever falhas em máquinas industriais, utilizando dados de sensores e informações operacionais.

2. Base de dados

O projeto utiliza uma base de dados de manutenção preditiva com 10.000 registros. A variável-alvo é `falha_maquina`, que indica se ocorreu uma falha na máquina.

3. Etapas do projeto

- Análise exploratória dos dados (EDA).
- Tratamento de valores ausentes e verificação de duplicatas.
- Análise de valores atípicos (outliers).
- Engenharia de atributos (*Feature Engineering*).
- Separação dos dados em conjuntos de treinamento e teste.
- Balanceamento das classes com SMOTE.
- Padronização das variáveis para o modelo KNN.
- Treinamento e avaliação dos modelos KNN e Árvore de Decisão.
- Comparação dos resultados e escolha do modelo final.

4. Modelos avaliados

Foram avaliados dois modelos de classificação: K-Nearest Neighbors (KNN) e Árvore de Decisão.

Nos testes realizados, a Árvore de Decisão com profundidade máxima igual a 10 apresentou acurácia de 95,15%, recall de 66,18% e F1-score de 0,4813 no conjunto de teste.

5. Conclusão

Entre as configurações avaliadas, a Árvore de Decisão apresentou os melhores resultados nas métricas comparadas. Entretanto, o modelo ainda deixou de identificar algumas falhas reais, sendo necessário aperfeiçoá-lo antes de qualquer aplicação em ambiente industrial.

6. Tecnologias utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

7. Como executar

Abra o notebook `projeto_analise_preditiva.ipynb` no Google Colab ou em um ambiente Jupyter Notebook e execute as células na ordem apresentada.
