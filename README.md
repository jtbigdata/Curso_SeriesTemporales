# **Curso Completo de Series Temporales (Beginner a Pro)**

---

## **Módulo 1: Introducción a las Series Temporales**
- **Conceptos clave**:
  - Definición y características de una serie temporal.
  - Componentes de una serie temporal: tendencia, estacionalidad, y ruido.
  - Tipos de series temporales: estacionarias y no estacionarias.
- **Proyecto**: Análisis exploratorio de una serie temporal.
  - Descargar un conjunto de datos de series temporales (por ejemplo, datos de clima o ventas) y graficar sus componentes básicos. Realizar un análisis descriptivo inicial.

---

## **Módulo 2: Preparación y Limpieza de Datos de Series Temporales**
- **Conceptos clave**:
  - Manejo de datos faltantes en series temporales.
  - Resampleo y agregación de series temporales.
  - Transformaciones de datos: diferencias logarítmicas, suavizamiento.
- **Proyecto**: Limpiar y preparar una serie temporal.
  - Descargar una serie temporal con valores faltantes (por ejemplo, precios de acciones) y aplicar técnicas de interpolación y suavizamiento para preparar los datos para análisis y modelado.

---

## **Módulo 3: Descomposición de Series Temporales**
- **Conceptos clave**:
  - Descomposición aditiva y multiplicativa de series temporales.
  - Identificación de tendencia, estacionalidad y residuos.
  - Aplicación de métodos de descomposición como STL (Seasonal and Trend decomposition using Loess).
- **Proyecto**: Descomponer una serie temporal.
  - Utilizar un conjunto de datos financieros o meteorológicos para descomponer la serie en sus componentes y analizar cómo cada uno contribuye al comportamiento general de la serie.

---

## **Módulo 4: Modelos Estadísticos Básicos: Promedios Móviles y Exponenciales**
- **Conceptos clave**:
  - Promedio Móvil Simple (SMA) y Exponencial (EMA).
  - Suavizamiento exponencial simple y de Holt-Winters.
  - Evaluación de modelos de suavizamiento con métricas como MSE y MAE.
- **Proyecto**: Implementar un modelo de suavizamiento exponencial.
  - Aplicar suavizamiento exponencial y el método de Holt-Winters para predecir tendencias en datos financieros o ventas. Comparar los resultados con los datos reales.

---

## **Módulo 5: Modelos ARMA y ARIMA**
- **Conceptos clave**:
  - Introducción a modelos AR (Autoregresivos), MA (Medias Móviles), ARMA y ARIMA.
  - Identificación de estacionariedad en series temporales (prueba de Dickey-Fuller).
  - Selección de parámetros para ARIMA (p, d, q) y validación del modelo.
- **Proyecto**: Ajustar un modelo ARIMA para predicción.
  - Aplicar ARIMA a una serie temporal de ventas o precios de acciones. Realizar validación cruzada y ajuste de parámetros para optimizar las predicciones.

---

## **Módulo 6: Modelos Estacionales SARIMA y SARIMAX**
- **Conceptos clave**:
  - Introducción al modelo SARIMA (ARIMA estacional).
  - Extender ARIMA con estacionalidad.
  - Incorporación de variables exógenas en SARIMAX y su impacto en la predicción.
- **Proyecto**: Implementar SARIMA y SARIMAX para predecir series temporales estacionales.
  - Utilizar datos estacionales (por ejemplo, ventas mensuales) y ajustarlos a un modelo SARIMA o SARIMAX. Evaluar la mejora en las predicciones respecto a modelos no estacionales.

---

## **Módulo 7: Modelos de Volatilidad: GARCH**
- **Conceptos clave**:
  - Introducción a la volatilidad en series temporales y su modelado.
  - Modelos GARCH (Generalized Autoregressive Conditional Heteroskedasticity).
  - Aplicaciones de GARCH para series temporales financieras y análisis de riesgo.
- **Proyecto**: Implementar un modelo GARCH.
  - Aplicar un modelo GARCH para predecir la volatilidad de precios de activos financieros (por ejemplo, precios de criptomonedas). Analizar cómo la volatilidad impacta en la toma de decisiones.

---

## **Módulo 8: Series Temporales con Machine Learning: Random Forest y XGBoost**
- **Conceptos clave**:
  - Uso de machine learning para series temporales.
  - Comparación entre modelos tradicionales y machine learning.
  - Entrenamiento de Random Forest y XGBoost para series temporales, manejo de features temporales.
- **Proyecto**: Implementar Random Forest y XGBoost para predicción de series temporales.
  - Comparar el desempeño de Random Forest y XGBoost en la predicción de precios de acciones o demanda de productos, utilizando métricas de evaluación y técnicas de validación cruzada.

---

## **Módulo 9: Redes Neuronales para Series Temporales**
- **Conceptos clave**:
  - Introducción a redes neuronales recurrentes (RNN) y su aplicación en series temporales.
  - Redes LSTM (Long Short-Term Memory) y su capacidad para capturar dependencias a largo plazo.
  - Uso de redes neuronales en predicción a largo plazo y técnicas de regularización.
- **Proyecto**: Implementar un modelo LSTM.
  - Usar LSTM para predecir el valor futuro de una serie temporal financiera o de demanda de productos. Evaluar la efectividad del modelo comparado con métodos tradicionales.

---

## **Módulo 10: Modelos Avanzados y Optimización**
- **Conceptos clave**:
  - Modelos avanzados: Prophet de Facebook y Modelos Híbridos (combinación de ARIMA + ML).
  - Optimización de hiperparámetros para modelos de series temporales.
  - Evaluación y comparación de modelos utilizando métricas avanzadas y análisis de errores.
- **Proyecto**: Implementar un modelo híbrido ARIMA + XGBoost o Prophet.
  - Utilizar Prophet o combinar ARIMA con un modelo de machine learning para mejorar las predicciones en un dataset complejo. Comparar el desempeño del modelo híbrido con los modelos individuales.

---

## **Módulo 11: Modelos Multivariados y Cointegración**
- **Conceptos clave**:
  - Introducción a modelos multivariados para series temporales (VAR, VECM).
  - Cointegración y sus implicaciones en el análisis de series temporales.
  - Pruebas de cointegración y modelos de corrección de errores.
- **Proyecto**: Aplicar modelos VAR o VECM a series temporales multivariadas.
  - Utilizar un conjunto de datos con múltiples series temporales (por ejemplo, variables económicas) para modelar sus interacciones y relaciones a largo plazo.

---

## **Módulo 12: Detección de Anomalías en Series Temporales**
- **Conceptos clave**:
  - Técnicas para detectar anomalías y puntos de cambio en series temporales.
  - Modelos basados en estadística y machine learning para detección de anomalías.
  - Métodos de visualización para anomalías en series temporales.
- **Proyecto**: Implementar un sistema de detección de anomalías.
  - Aplicar técnicas de detección de anomalías a una serie temporal (por ejemplo, datos de sensores) y evaluar la capacidad del modelo para identificar eventos inusuales.

---

## **Módulo 13: Series Temporales y Análisis de Regresión**
- **Conceptos clave**:
  - Aplicación de técnicas de regresión para modelar series temporales.
  - Modelos de regresión con componentes de series temporales (Regresión ARIMA, Regresión Dinámica).
  - Evaluación de la relación entre series temporales y variables predictoras.
- **Proyecto**: Implementar un modelo de regresión para series temporales.
  - Usar técnicas de regresión para modelar una serie temporal y evaluar el impacto de variables externas en la serie temporal.

---

## **Proyecto Final**
- **Descripción**: El proyecto final consistirá en aplicar una combinación de técnicas aprendidas a lo largo del curso para resolver un problema real de series temporales. Selecciona un conjunto de datos complejo, como precios de acciones, demanda de energía o ventas de productos, y aplica técnicas como ARIMA, SARIMA, GARCH, LSTM, y modelos de machine learning para construir un sistema de predicción integral. Evalúa el rendimiento de cada modelo y proporciona recomendaciones basadas en el análisis comparativo.

---
