# Previsão de AVC com Random Forest e XGBoost usando SMOTE

##  Integrantes
-  **Cleverson Pereira da Silva – RA 10391119**  

---

##  Objetivo
O objetivo deste projeto é **prever a ocorrência de Acidente Vascular Cerebral (AVC)** a partir de dados clínicos e demográficos, aplicando técnicas de **aprendizado de máquina supervisionado**.  

A solução utiliza:  
 **Balanceamento de classes com SMOTE**  
 **Modelos Random Forest e XGBoost**  
 **Métricas robustas de avaliação**  

---

##  Dataset
 **Arquivo:** `healthcare-dataset-stroke-data.csv`  
 **Descrição:** Conjunto de dados sobre fatores de risco para AVC (idade, gênero, histórico de doenças, estilo de vida, etc.).  

 **Etapas de pré-processamento:**  
- Tratamento de valores ausentes  
- Balanceamento com **SMOTE**  
- Normalização e codificação de variáveis categóricas  

---

##  Metodologia
1.  **Análise Exploratória de Dados (EDA)** – estatísticas descritivas e gráficos.  
2.  **Pré-processamento** – balanceamento com SMOTE e divisão treino/teste.  
3.  **Modelagem** – treinamento com **Random Forest** e **XGBoost**.  
4.  **Avaliação** – métricas como Acurácia, Precisão, Recall, F1-Score e Matriz de Confusão.  
5.  **Comparação de Resultados** – identificação do modelo de melhor desempenho.  

