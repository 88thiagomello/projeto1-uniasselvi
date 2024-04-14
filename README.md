# Projeto I - Aplicação de Métodos de Aprendizagem de Máquina

## Descrição do Tema
O tema escolhido para este projeto é a análise de dados relacionados à saúde pública utilizando o conjunto de dados disponível no Kaggle, intitulado ["Healthcare Dataset Stroke Data"](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data). Este conjunto de dados contém informações sobre pacientes, incluindo variáveis como idade, gênero, índice de massa corporal (IMC), estado civil, tipo de trabalho, entre outras. O foco principal será na previsão de acidentes vasculares cerebrais (AVCs) com base nessas variáveis, utilizando métodos de aprendizagem de máquina.

## Objetivo
O objetivo principal deste projeto é desenvolver um modelo de machine learning capaz de prever a ocorrência de AVCs com base nos dados de pacientes disponíveis. Além disso, busca-se identificar os principais fatores de risco associados a AVCs e entender como essas variáveis podem influenciar as previsões do modelo. A aplicação prática dessa análise pode contribuir para a identificação precoce de possíveis pacientes em risco, permitindo a intervenção médica adequada.

## Especificação Técnica
1. **Campos da Base de Dados:**
   - ID do paciente
   - Idade
   - Gênero
   - Hipertensão
   - Doença cardíaca
   - Estado civil
   - Tipo de trabalho
   - Residência urbana/rural
   - IMC
   - Fumante ou não
   - Nível de atividade física
   - AVC (variável alvo)

2. **Tipos de Dados:**
   - Numéricos (idade, IMC)
   - Categóricos (gênero, estado civil, tipo de trabalho)
   - Binários (hipertensão, doença cardíaca, fumante, AVC)
   - Ordinais (nível de atividade física)

3. **Métodos de Machine Learning:**
   - Algoritmos de classificação, como Random Forest, Support Vector Machines (SVM) e Regressão Logística.

4. **Divisão da Base de Dados:**
   - Treinamento: 70%
   - Teste: 30%

5. **Métricas de Avaliação:**
   - Precisão (Accuracy)
   - Sensibilidade (Recall)
   - Especificidade
   - Área sob a curva ROC (AUC-ROC)

Ao final do projeto, pretende-se apresentar um modelo robusto que possa ser utilizado para prever a probabilidade de ocorrência de AVCs com base nas informações fornecidas pelos pacientes. Isso pode ser valioso para profissionais de saúde na identificação de grupos de risco e na implementação de medidas preventivas.
