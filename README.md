# Credit Risk Analysis
Project made during the Neural Network Class lessons at CIn UFPE graduation.  
Dataset can be downloaded at: https://drive.google.com/file/d/1Lml4_zxSEaZc-WIo_vVOyFwtzWS_hh40/view?usp=drive_web&authuser=1

#Redes Neurais - Plano de Projeto
Pietro Masur - Ewerton Bernardo
Objetivo: 
Treinar um modelo de redes neurais para classificação de dados de risco de crédito.

##Metodologia:  
Testes empíricos com vários modelos diferentes, onde cada um deles será avaliado através de métricas comuns e investigado através de um grid search.  
  
###Parâmetros comuns a todos os métodos:  
Épocas = 10.000  
Paciência = 20  
###Métricas de avaliação: 
   KS
   MSE
   Matriz de Confusão
   Auroc
   Classification-Report (Recall, Precision e F-Measure)

###Passo 1:
MLP:  
Optimizers: [SGD, Adam, Adagrad]  
LRs: [0.005, 0.015, 0.3]  
Hidden Layers: [1,2]  
Numbers of neurons: [5,30,100]  
Activation Function on Hidden Layer: [ReLU, Sigmoid, Tanh]  
  
Random Forests:
  
###Passo 2:  
Esemble de MLPs  
Gradient Boosting  
Esemble de classificadores  
SVM  
