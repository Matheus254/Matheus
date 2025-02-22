# Projeto de Previsão de Diabetes

Projeto de Machine Learning para prever se um paciente terá diabetes com base em características clínicas.

## 🎯 Objetivo
Desenvolver um modelo de classificação capaz de prever a ocorrência de diabetes com alta precisão, utilizando algoritmos clássicos de Machine Learning.

## 📋 Pré-requisitos
- Python 3.8+
- Bibliotecas listadas em `requirements.txt`

## 📦 Instalação
```bash
pip install -r requirements.txt
```

## 🔍 Análise de Desempenho
Priorizamos **Recall (Sensibilidade)** para minimizar falsos negativos, críticos em diagnósticos médicos.  
Apesar da alta acurácia (93.27%), o modelo falha em detectar **12% dos casos de diabetes** (Recall = 88.18%), indicando espaço para melhorias no balanceamento de classes ou ajuste do limiar de classificação.

**Métricas-Chave:**
- Acurácia: 93.27%  
- Precisão: 91.50%  
- Recall: 88.18%  
- AUC: 98.21% *(Excelente capacidade de distinção entre classes)*

## 💻Modelos usados
- Regressão Logística 
- Random Forest Classifier
