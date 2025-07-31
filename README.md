# Telecom X - Análisis de Evasión de Clientes

## 🎯 Objetivo
Este proyecto busca comprender los factores que influyen en la tasa de evasión de clientes (churn) en Telecom X, aplicando procesos de ETL, análisis exploratorio y visualización de datos para extraer insights valiosos que ayuden a reducir el abandono de clientes.

## 🧰 Herramientas Utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 📂 Estructura del Proyecto
- **TelecomX_Churn_Analysis_Agustin.ipynb**: Cuaderno principal con todo el análisis.
- **TelecomX_Data.json**: Archivo de datos en formato JSON.
- **TelecomX_diccionario.md**: Diccionario de datos con la descripción de las columnas.
- **/TelecomX_Outputs/**: Carpeta que contiene los gráficos generados.

## 🚀 Instrucciones de Ejecución
1. Abre el archivo `TelecomX_Churn_Analysis_Agustin.ipynb` en Google Colab.
2. Asegúrate de subir el archivo `TelecomX_Data.json` al entorno de ejecución.
3. Ejecuta las celdas secuencialmente.
4. Revisa las visualizaciones y conclusiones al final del cuaderno.

## 📊 Principales Insights
- Los contratos de tipo **"Month-to-month"** están fuertemente asociados a la evasión.
- El método de pago **"Electronic check"** se correlaciona con una mayor tasa de churn.
- Clientes con mayor **gasto mensual** y **bajo tiempo de permanencia** son más propensos a cancelar.

## ✅ Recomendaciones Estratégicas
- Fomentar el uso de contratos anuales o bianuales.
- Diseñar alertas preventivas para clientes con mayor riesgo de churn.
- Enfocar promociones y beneficios a clientes con múltiples servicios y pago electrónico.

## 📎 Créditos
Desarrollado por Agustín Muñoz como parte del desafío de análisis de datos de Alura LATAM.
