# 📈 Análisis de Datos Financieros & Reportes con IA / Financial Data Analysis & AI Reports

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?logo=visualstudiocode)](https://vscode.dev/github/stiven-escobar/proyecto03_analisis_de_datos_python)
[![Render Interactive Charts (nbviewer)](https://img.shields.io/badge/Render-Interactive%20Charts-orange?logo=jupyter)](https://nbviewer.org/github/stiven-escobar/proyecto03_analisis_de_datos_python/tree/main/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Data-3F4F75?logo=plotly)](https://plotly.com/)
[![Google Gemini API](https://img.shields.io/badge/AI-Google%20Gemini-8E75B2?logo=google)](https://ai.google.dev/)

---

## 🌐 Español

### 📌 Descripción del Proyecto
Este proyecto es una solución analítica avanzada desarrollada en Python que combina la **extracción de datos del mercado financiero**, **visualización de datos interactiva** y la integración de **Inteligencia Artificial Generativa** para el análisis macroeconómico automatizado.

A partir del historial de precios de cierre del último año de acciones tecnológicas líderes (**Apple - `AAPL`**, **Microsoft - `MSFT`** y **Nvidia - `NVDA`**), el sistema procesa estadísticas descriptivas, simula el rendimiento de una inversión de **$1,000 USD** y genera un reporte cualitativo detallado utilizando la API de **Google Gemini** (`gemini-2.5-flash`).

### 🛠️ Tecnologías y Librerías Utilizadas
* **`yfinance`**: Descarga de series temporales de activos financieros.
* **`pandas`**: Manipulación, limpieza y estructuración de DataFrames de precios.
* **`plotly` (`plotly.express`)**: Generación de gráficos e histogramas interactivos interconectados.
* **`google-genai`**: Integración con el LLM de Google Gemini para la redacción automática de informes analíticos sobre los factores del mercado.

### ⚙️ Funcionalidades Principales
1. **Extracción Multiactivo**: Consulta automatizada de la cotización histórica de Apple, Microsoft y Nvidia.
2. **Estadística Descriptiva de Mercados**: Cálculo de promedios, desviaciones estándar, rangos de volatilidad y precios máximos/mínimos.
3. **Simulador de Inversión ($1000 USD)**: Análisis comparativo de crecimiento del capital invertido en los distintos activos durante los últimos 12 meses.
4. **Visualizaciones Interactivas**:
   * Gráficos de línea con serie temporal histórica.
   * Diagramas de barras comparativos de precios promedio.
   * Exportación de gráficos interactivos a formato HTML (`inversion de 1000 USD.html`).
5. **Generación de Reportes con IA**: Prompting automatizado a Google Gemini para sintetizar los eventos financieros, lanzamientos tecnológicas y noticias del mercado que explican la tendencia del período.

---

## 📊 ¿Cómo abrir e interactuar con los Gráficos Interactivos?
Debido a que GitHub desactiva la interactividad JavaScript en los archivos `.ipynb` por defecto, puedes visualizar los gráficos de **Plotly** con zoom, hovering y selección de series mediante cualquiera de las siguientes opciones:

1. **Vía nbviewer (Recomendado)**: Haz clic en el botón [![Render Interactive Charts](https://img.shields.io/badge/Render-Interactive%20Charts-orange?logo=jupyter)](https://nbviewer.org/github/stiven-escobar/proyecto03_analisis_de_datos_python/tree/main/) en la parte superior.
2. **Archivo HTML standalone**: Descarga y abre directamente en tu navegador el archivo generado `inversion de 1000 USD.html`.
3. **Entorno local o VS Code**: Ejecuta el Jupyter Notebook localmente activando la extensión de Plotly o el entorno interactivo de VS Code.

---

## 🌐 English

### 📌 Project Overview
This project is an advanced financial analytics pipeline built in Python that merges **financial market data retrieval**, **interactive data visualization**, and **Generative AI integration** for automated market analysis.

By extracting the trailing 12-month closing prices of top-tier tech equities (**Apple - `AAPL`**, **Microsoft - `MSFT`**, and **Nvidia - `NVDA`**), the system computes summary statistics, models a **$1,000 USD** investment growth trajectory, and triggers **Google Gemini API** (`gemini-2.5-flash`) to author a market research report explaining price dynamics.

### 🛠️ Tech Stack & Dependencies
* **`yfinance`**: Time-series stock market data extraction.
* **`pandas`**: High-performance data manipulation and DataFrame structuring.
* **`plotly` (`plotly.express`)**: Interactive time-series and bar chart visualizations.
* **`google-genai`**: Google Gemini LLM API integration for automated market insights generation.

### ⚙️ Key Features
1. **Multi-Asset Extraction**: Automated retrieval of historical price series for Apple, Microsoft, and Nvidia.
2. **Descriptive Financial Statistics**: Automatic computation of mean, standard deviation, volatility ranges, and min/max boundaries.
3. **$1,000 USD Investment Simulator**: Comparative capital returns modeling across selected stocks over the trailing year.
4. **Interactive Data Visualizations**:
   * Interactive historical price trend line charts.
   * Comparative average pricing bar charts.
   * Standalone HTML export (`inversion de 1000 USD.html`) for browser-native chart interactivity.
5. **AI-Powered Financial Reporting**: Dynamic prompt orchestration sending financial metrics to Google Gemini to interpret market drivers, macro news, and product launches.

---

## 📊 How to View Interactive Charts
Since GitHub strips JavaScript execution from Jupyter Notebook previews, interactive features (zoom, pan, hover tooltips) for **Plotly** graphs can be accessed through:

1. **nbviewer Renderer (Recommended)**: Click the [![Render Interactive Charts](https://img.shields.io/badge/Render-Interactive%20Charts-orange?logo=jupyter)](https://nbviewer.org/github/stiven-escobar/proyecto03_analisis_de_datos_python/tree/main/) badge above.
2. **HTML Export**: Download and open the `inversion de 1000 USD.html` file directly in any browser.
3. **Local VS Code Execution**: Run the Jupyter Notebook inside VS Code with the interactive renderer enabled.

---

## 👤 Autor / Author

**Stiven Escobar Carabalí**  
* Profesional en Administración Comercial y Mercadeo
* Tecnólogo en Análisis y Desarrollo de Software (ADSO)
* Especialista en Analítica de Datos

[![GitHub](https://img.shields.io/badge/GitHub-stiven--escobar-181717?logo=github)](https://github.com/stiven-escobar)
