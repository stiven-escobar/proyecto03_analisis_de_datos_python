# 📊 AI-Powered Stock Market Analysis & Interactive Data Analytics / Análisis Bursátil con IA y Visualización Interactiva

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?style=flat&logo=visualstudiocode)](https://vscode.dev/github/Kykyo2026/proyecto03_analisis_de_datos_python/blob/main/proyecto03.ipynb)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![yfinance](https://img.shields.io/badge/API-yfinance-green)
![Plotly](https://img.shields.io/badge/Data%20Viz-Plotly-purple)
![Google Gemini AI](https://img.shields.io/badge/AI-Google%20Gemini-orange?logo=google)

---

## 🌐 English Description

### 📝 Overview
An advanced **Financial Data Analytics** and **Generative AI** project developed in Python. The system ingests financial data for tech leaders (**Apple**, **Microsoft**, and **Nvidia**) using `yfinance`, performs interactive exploratory data analysis (EDA) with `Plotly`, simulates investment scenarios, and integrates **Google Gemini API** to generate automated financial executive reports based on market performance.

### 🎯 Key Features
1. **Multi-Asset Data Ingestion:** Automates fetching 12-month historical stock prices for `AAPL`, `MSFT`, and `NVDA` via `yfinance`.
2. **Interactive Data Visualization (`Plotly`):**
   * **Historical Price Trends:** Interactive multi-asset price evolution over time.
   * **Average Valuation Benchmarks:** Bar charts evaluating mean price comparisons.
   * **ROI Investment Simulator:** Dynamic calculation and interactive chart simulating the current value of a $1,000 USD initial investment.
   * **HTML Export:** Exportable standalone interactive charts (`fig.write_html`).
3. **Generative AI Financial Reports (`Google Gemini API`):**
   * Automated prompt engineering connecting quantitative financial metrics to Gemini (`gemini-2.5-flash`).
   * Synthesis of automated financial executive summaries explaining market growth drivers, stock split impacts, and AI market trends.

### 🛠️ Tech Stack & Libraries
* **Python 3.x**
* **Data Processing:** `pandas`, `numpy`
* **Data Extraction:** `yfinance`
* **Interactive Visualization:** `plotly.express`
* **Generative AI:** `google-genai` (Google Gemini API)

---

## 🌐 Descripción en Español

### 📝 Descripción General
Proyecto avanzado de **Analítica de Datos Financieros e Inteligencia Artificial Generativa** desarrollado en Python. El sistema extrae automáticamente datos de cotización bursátil para empresas líderes tecnológicas (**Apple**, **Microsoft** y **Nvidia**) a través de `yfinance`, realiza análisis exploratorio interactivo (EDA) con `Plotly`, simula escenarios de retorno de inversión y se conecta a la API de **Google Gemini** para redactar informes ejecutivos financieros automatizados.

### 🎯 Funcionalidades Clave
1. **Ingesta de Datos Multiactivo:** Descarga automatizada de 12 meses de historial de precios para `AAPL`, `MSFT` y `NVDA`.
2. **Visualización Interactiva (`Plotly`):**
   * **Evolución Histórica:** Gráficos de línea dinámicos con zoom y tooltips interactivos.
   * **Comparativa de Precio Promedio:** Gráfico de barras comparativo de valoración media.
   * **Simulador de Retorno de Inversión (ROI):** Cálculo y visualización dinámica del valor actual de una inversión inicial de $1,000 USD.
   * **Exportación HTML:** Guardado automático de dashboards interactivos e independientes en formato `.html`.
3. **Informes Financieros con IA Generativa (`Google Gemini API`):**
   * Integración directa con modelos de lenguaje de Gemini (`gemini-2.5-flash`).
   * Redacción automática de informes ejecutivos que interpretan las métricas cuantitativas y explican eventos clave de mercado (adopción de IA, resultados trimestrales, etc.).

---

## 🚀 How to Run & View Interactive Charts / Cómo Ejecutar y Visualizar

### 💻 Interactive Preview / Vista Interactiva
To explore the fully interactive `Plotly` graphs and execution outputs, open the notebook directly in **VS Code for Web**:  
👉 [**Open Project 03 in VS Code Web**](https://vscode.dev/github/Kykyo2026/proyecto03_analisis_de_datos_python/blob/main/proyecto03.ipynb)

### 🐍 Local Setup / Configuración Local
1. Clone the repository / Clona el repositorio:
   ```bash
   git clone [https://github.com/Kykyo2026/proyecto03_analisis_de_datos_python.git](https://github.com/Kykyo2026/proyecto03_analisis_de_datos_python.git)
