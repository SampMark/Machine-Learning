# 💻 **_Machine Learning_** 🧑‍💻

Bem-vindo 🤗 ao repositório de estudos sobre Ciência de Dados, com foco Análises Exploratória de Dados e modelagens em _machine learning_ aplicadas à ciência de dados e análise. 

A modelagem em machine learning consiste no processo de criar, treinar e validar modelos computacionais que aprendem padrões a partir de dados. Consiste numa gama de modelagens amplamente utilizados para resolver problemas complexos em diversas áreas, os quais envolvem a previsão (regressão), classificação, agrupamento/segmentação e detecção de anomalias (por exemplo, _outliers_). Em linhas gerais, o aprendizado de máquina visa projetar, entender e aplicar programas de computador que aprendem com a experiência, consistindo como uma de suas principais tarefas a **previsão**.

Pode ser empregado em múltiplas aplicações, incluindo pesquisa na web, recomendações de filmes, sistemas automatizados, análise de imagens e jogos. O aprendizado de máquina também está sendo adotado por diferentes disciplinas, como biologia, química e física. 
Ou ainda, na previsão de eventos futuros, como o valor de mercado de uma ação ou a propensão de determinado paciente adquirir uma doença.

---

## 🎯 **Visualização e Análise de Dados:**
- Exemplos práticos para Análise Exploratória de Dados usando bibliotecas como:
- **Matplotlib** para criação de gráficos e visualizações;
- **Pandas** para manipulação e análise de dados;
- **Seaborn** para visualização e análieses estatística de dados;
- **Numpy** para computação numérica, incluindo arrays multidimensionais.

## 🚀 **Machine Learning:** 
- Construção e avaliação de modelos de regressão, classificação e agrupamento usando bibliotecas, como:
- **Scikit-learn** para modelagens preditivas usando aprendizado de máquina.
- **SnapML**, desenvolvida pela IBM, com ênfase em alto desempenho e escalabilidade, projetada para lidar com grandes volumes de dados, utilizando técnicas de paralelismo e aceleração por GPU.

## 🌟 **Objetivos:**
- Compartilhar soluções didáticas e bem documentadas para quem está estudando Ciência de Dados, servindo como base de consulta.

## 📝 **Conteúdo do Repositório**
- Introdução ao Aprendizado de Máquina:
  - [**Risco Empírico e a Função de Perda (_hinge loss_)**: técnicas comumente usadas para treinar SVMs e outros classificadores lineares](https://github.com/SampMark/Machine-Learning/blob/main/Hinge_Loss.ipynb)
  - [**Gradiente Descendente e Regularização**: uma abordagem matemática e computacional aplicada](https://github.com/SampMark/Machine-Learning/blob/main/Gradient_Descent_and_Regularization.ipynb)
  - [**Algoritmo Perceptron** -  introdução as redes neurais](https://github.com/SampMark/Machine-Learning/blob/main/Perceptron_Algorithm.ipynb)
  - [**Função Softmax** - técnica essencial de classificação multi-classe](https://github.com/SampMark/Machine-Learning/blob/main/Softmax_Multinomial_Regression.ipynb)
  - [**Função de custo de entropia cruzada com regularização L2 (_Log Loss Cross-Entropy_)**](https://github.com/SampMark/Machine-Learning/blob/main/Log_Loss_Cross_Entropy.ipynb)
  - [**Introdução as Redes Neurais**](https://github.com/SampMark/Machine-Learning/blob/main/Neural_Networks.ipynb)
  
- Modelagens utilizando _Machine Learning_:
- **Regressão**: problemas cujo objetivo é estimar um valor contínuo baseado ou probabilidade em variáveis de entrada.
  - [Regressão Linear Simples](https://github.com/SampMark/Machine-Learning/blob/main/ML01_Simple_Linear_Regression.ipynb) e [Múltipla](https://github.com/SampMark/Machine-Learn/blob/main/Multiple_Linear_Regression.ipynb)
  - [Regressão Polinomial](https://github.com/SampMark/Machine-Learn/blob/main/Polynomial_Regression.ipynb)
  - [Regressão Logística](https://github.com/SampMark/Machine-Learn/blob/main/Logistic_Regression.ipynb)
- **Classificação**: problemas cujo objetivo é atribuir um rótulo discreto a uma entrada.
  - [K-Vizinhos Mais Próximos (_K-Nearest Neighbors_ K-NN)](https://github.com/SampMark/Machine-Learn/blob/main/K_Nearest_Neighbors.ipynb)
  - [Árvores de Decisão (_Decision Trees_)](https://github.com/SampMark/Machine-Learn/blob/main/Decision_Trees.ipynb)
  - [Máquina de Vetores de Suporte (_Support Vector Machines_)](https://github.com/SampMark/Machine-Learn/blob/main/SVM_Support_Vector_Machines.ipynb)
  - [Support Vector Machines (SVM) aplicado à detecção de fraudes em transações](https://github.com/SampMark/Machine-Learn/blob/main/SVM_Applied_to_Transaction_Fraud_Detection.ipynb)
 
    ### Problemas de Classificação vs. Regressão: Diferenças Fundamentais
    
    | Característica    | Classificação                                      | Regressão                                    |
    |------------------|--------------------------------------------------|----------------------------------------------|
    | Tipo de saída    | Discreta (categorias)                             | Contínua (números reais)                    |
    | Modelo de decisão | Baseia-se em limites de decisão entre classes   | Baseia-se em funções matemáticas que minimizam erro contínuo |
    | Algoritmos comuns | k-NN, Árvores de decisão, SVM, Redes Neurais     | Regressão Linear e Polinomial, Logística, Redes Neurais |
    | Métricas de avaliação | Acurácia, Precisão, Recall, F1-score      | RMSE (Root Mean Squared Error), MAE (Mean Absolute Error) |

- **Agrupamento/Clustering**
  - [**K-Means**](https://github.com/SampMark/Machine-Learn/blob/main/k_Means_with_a_randomly_generated_dataset.ipynb)
  - [**K-Means**, aplicado à segmentação de clientes](https://github.com/SampMark/Machine-Learn/blob/main/k_Means_applied_to_customer_segmentation.ipynb)
  - [**K-Means** vs. **_Expectation-Maximization_(EM)**: _Gaussian Mixture Model_ (GMM)](https://github.com/SampMark/Machine-Learning/blob/main/Gaussian_Mixture_Model_(GMM)_K_Means_vs_Expectation_Maximization_(EM).ipynb)
  - [**Agrupamento Hierárquico Aglomerativo** (_Agglomerative Hierarchical Clustering_)](https://github.com/SampMark/Machine-Learn/blob/main/Agglomerative_Hierarchical_Clustering.ipynb)
  - [**Agrupamento Hierárquico Aglomerativo**: aplicado à análise de mercado automotivo](https://github.com/SampMark/Machine-Learn/blob/main/Agglomerative_Hierarchical_Clustering_applied_to_automotive_market_analysis.ipynb)
  - [**DBSCAN**: Clusterização espacial utilizando dados de estações meteorológicas do Canada](https://github.com/SampMark/Machine-Learn/blob/main/DBSCAN_Clustering_Weather_Station.ipynb)
- **Comparação de Desempenho Preditivo**:
  - [Comparação simplificada do desempenho dos modelos KNN, Decision Tree, SVM e Logistic Regression](https://github.com/SampMark/Machine-Learn/blob/main/Comparison_Models_for_Predicting_Basketball_Tournament_Outcomes.ipynb)  
  - [Modelagem completa e comparação de modelos em machine learn para prever resultados de torneios de basquete](https://github.com/SampMark/Machine-Learn/blob/main/Prediction_in_Basketball_Tournament_Comparison_Between_Machine_Learn_Models.ipynb)
 
- **Sistema de Classificação para Análise de Sentimentos/Opiniões**
  - Este notebook proporciona uma visão prática sobre aprendizado de máquina aplicado à análise de sentimentos em relação a opiniões sobre produtos ou serviços. O objetivo é treinar e avaliar classificadores lineares (Perceptron, Perceptron Médio e Pegasos) para identificar opiniões avaliações positivas (+1) ou negativas (-1)​.
  
    **Tópicos abordados**: 
    * ✅ Implementação e comparação de algoritmos de classificação
    * ✅ Ajuste de hiperparâmetros para otimização de desempenho
    * ✅ Análise gráfica dos resultados
  
  Assim, é possível entender melhor como construir um "[Classificador de Sentimentos/Opiniões sobre Produtos e/ou Serviços](https://github.com/SampMark/Machine-Learning/blob/main/Sentiment_Analysis___an_introduction_to_machine_learning_algorithms.ipynb)", mas também sobre como avaliar e melhorar o desempenho de modelos de aprendizado de máquina. 

## <div style="display: flex; align-items: center; gap: 10px; border: 0; padding: 10px;">

  <img src="https://github.com/user-attachments/assets/8d25464f-0d04-450d-907c-c932c6fef15e" alt="Badge IBM" width="150" style="border: none;">

  <p>
    <strong>Machine Learning with Python</strong><br>
    This credential earner understands the basics of machine learning using Python such as: 
    Distinguishing the difference between the two main types of machine learning methods: supervised & unsupervised; 
    Identifying supervised learning algorithms, including classification & regression; 
    Identifying unsupervised learning algorithms, including Clustering & Dimensionality Reduction; 
    Determining how statistical modeling relates to machine learning & comparing them; 
    How machine learning affects society.
  </p>

</div>
    
## 📚 **Referências**

- BARROS, Thiago Medeiros. **Um processo orientado a dados para geração de modelo de predição de evasão escolar** / tese (doutorado) - PPgEEC/UFRN, Natal/RN, 2020.
- GÉRON, A. **Hands-On machine learning with scikit-learn, keras & tensorflow farnham**. Canada: O’Reilly, 2023.
- GUJARATI, Damodar N. **Essentials of econometrics**. Sage Publications, 2021.
- PEDREGOSA _et al_. **Scikit-learn: Machine Learning in Python**, [Journal of Machine Learning Research (JMLR)](https://jmlr.org/) 12, pp. 2825-2830, 2011.
- Goodfellow _et al_. **Deep Learning**. Autores: Ian Goodfellow and Yoshua Bengio and Aaron Courville, MIT Press, 2016. Disponível em: [http://www.deeplearningbook.org](http://www.deeplearningbook.org)

---

## 🤝 **Contribuições**

Contribuições são bem-vindas! Se você deseja aprimorar as soluções ou adicionar explicações, sinta-se à vontade para abrir um _Pull Request_.

---

**🚀 Compartilhe conhecimento e inspire futuros cientistas de dados!**
