# 🕵️‍♀️ Detecção de Fraudes em Transações Financeiras com Python

## 📌 Sobre o Projeto

Este projeto tem como objetivo identificar padrões suspeitos em transações financeiras utilizando técnicas de análise de dados.

A solução foi desenvolvida em Python no ambiente Google Colab, explorando dados de transações contendo informações como valor, localização, horário, categoria e canal de compra.

---

## 🎯 Objetivos

* Identificar transações fraudulentas
* Analisar padrões de comportamento
* Validar a solução com testes automatizados

---

## 🧠 Tecnologias Utilizadas

* Python 3
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Pytest
* Google Colab

---

## 📊 Análise Exploratória (EDA)

Foram realizadas análises para entender o comportamento das transações:

### 🔹 Distribuição de Fraudes

* Avaliação da proporção de fraudes no dataset

### 🔹 Análise por Horário

* Fraudes concentradas na madrugada

### 🔹 Análise por Localização

* Maior incidência em transações internacionais

### 🔹 Distribuição de Valores

* Fraudes associadas a valores extremos (altos ou muito baixos)

---

## 🚨 Regras de Detecção (Heurística)

Foi implementada uma função baseada em regras:

* Valores acima de 5000 → suspeito
* Transações na madrugada → suspeito
* Localizações internacionais → suspeito

---

### 📌 Features utilizadas:

* Valor da transação
* Categoria
* Canal
* Localização
* Hora

### 📊 Métricas avaliadas:

* Accuracy
* Precision
* Recall

---

## 🧪 Testes Automatizados

Foram criados testes com Pytest para garantir a qualidade do código:

### ✔️ Casos testados:

* Transações com valor alto
* Transações na madrugada
* Localização suspeita
* Transações normais

---

## 🔍 Principais Insights

* Fraudes ocorrem principalmente em horários incomuns
* Transações internacionais possuem maior risco
* Valores muito altos são fortes indicadores
* Padrões repetitivos em curto tempo indicam possível ataque

---

## 🚀 Possíveis Melhorias

* Implementar modelos mais avançados (Random Forest, XGBoost)
* Criar dashboard interativo com Streamlit
* Aplicar detecção de anomalias (Isolation Forest)
* Integrar com API para análise em tempo real

---

## 💼 Aplicação no Mundo Real

Este projeto simula cenários utilizados por fintechs e bancos para:

* Prevenção de fraudes
* Análise de risco
* Monitoramento de transações em tempo real

---

## 👩‍💻 Autora

Projeto desenvolvido por Thayza ✨


---
