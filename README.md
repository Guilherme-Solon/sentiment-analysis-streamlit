# sentiment-analysis-streamlit

# Integrantes - Guilherme Alexsander Vaz Solon 5157515 / Kauã Nogueira Costa 5157361

# 🧠 Análise de Sentimentos com Streamlit

Este projeto foi desenvolvido como trabalho final da disciplina **Ciência de Dados**. Trata-se de uma aplicação interativa construída com **Python** e **Streamlit** que realiza a análise de sentimentos com base em um dataset de textos rotulados. O modelo classifica frases como **positivas** ou **negativas** após um processo completo de pré-processamento e modelagem.

---

## 📌 Objetivo

Desenvolver uma aplicação funcional de Ciência de Dados capaz de:

- Pré-processar textos com NLTK
- Visualizar a distribuição de sentimentos
- Treinar um modelo Naive Bayes para classificação
- Apresentar resultados em gráficos e relatórios
- Permitir que o usuário insira uma frase e receba o sentimento previsto

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python
- Streamlit
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- NLTK
- Pyngrok

---

## 🧪 Etapas do Projeto

- ✅ Coleta de dados (`sentimentdataset.csv`)
- ✅ Pré-processamento com NLTK (stopwords, lematização)
- ✅ Análise exploratória (visualização com Seaborn)
- ✅ Modelagem (Naive Bayes)
- ✅ Deploy local com Streamlit + ngrok

---

## 🚀 Como Executar Localmente no Google Colab

1. Instale as dependências:

```bash
!pip install -q streamlit pyngrok nltk matplotlib seaborn

!ngrok config add-authtoken 2yhUsc2S4Kiy2yn3IFFAvHpfbFM_6xEJQWbWDwe33A5bgUZfP

!nohup streamlit run app.py --server.port 8501 &

from pyngrok import ngrok
public_url = ngrok.connect(8501)
print(public_url)


![image](https://github.com/user-attachments/assets/97fa4cc9-f39a-4be2-8242-9b780ae747ba)
