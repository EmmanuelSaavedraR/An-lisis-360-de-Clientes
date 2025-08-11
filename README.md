# 📊 Analisis-360-de-Clientes
Análisis 360° de clientes y respuesta a campañas de marketing utilizando Python para limpieza de datos, modelado en Power BI con dimensiones optimizadas, y visualizaciones interactivas para segmentación, hábitos de compra y efectividad de campañas. Proyecto basado en dataset público de Kaggle, adaptado a un escenario empresarial real.
# Análisis 360° de Clientes – Segmentación y Comportamiento

## 📌 Introducción
Este proyecto presenta un análisis integral de clientes de una compañía ficticia de retail, con el objetivo de **predecir la probabilidad de respuesta a campañas de marketing** y **optimizar la segmentación** para maximizar el retorno de inversión publicitaria.  
El dataset utilizado proviene de **Kaggle** (Customer Personality Analysis Dataset) y se adaptó para crear un escenario realista de negocio.

El proyecto desarrolla un flujo completo:
1. Limpieza y preparación de datos en **Python**.
2. Creación de **dimensiones y modelo de datos** en Power BI.
3. Diseño de **dashboards interactivos** para el análisis 360° del cliente.

---

## 🏢 Historia del proyecto
Imaginemos que trabajamos en el área de análisis de una empresa de retail que ha realizado múltiples campañas de marketing, pero necesita:
- Identificar qué tipo de clientes son más propensos a aceptar ofertas.
- Conocer cómo sus hábitos de consumo impactan en la efectividad de campañas.
- Segmentar de forma más eficiente para reducir costos y aumentar ingresos.

A partir de datos históricos de consumo, demografía y respuesta a campañas, se desarrolló un modelo analítico que permite:
- Medir la tasa de respuesta por segmento.
- Analizar el gasto promedio por categoría de producto.
- Visualizar patrones de compra y visitas web.
- Predecir segmentos con mayor potencial de conversión.

---

## 🎯 Hipótesis
**Hipótesis principal:**  
Clientes con mayor gasto acumulado en productos premium (vinos y oro) y compras recientes tienen más probabilidad de responder a campañas.

**Hipótesis secundarias:**  
1. Clientes con mayor interacción digital (compras web y visitas) responden mejor a campañas online.  
2. Nivel de ingresos y estado civil influyen en la aceptación de campañas.  
3. La tasa de aceptación aumenta en clientes con historial positivo en campañas previas.

---

## 🛠 Metodología

### 1. Limpieza y preparación de datos (Python)
- Librerías: `pandas`, `numpy`.
- Conversión de variables de texto a formato estandarizado.
- Manejo de valores nulos y codificación de variables categóricas.
- Creación de nuevas variables derivadas (ej. generación a partir del año de nacimiento).
- Exportación del dataset limpio para integración en Power BI.

### 2. Creación de dimensiones (Power BI)
- Separación de la tabla de hechos (transacciones y respuestas) y dimensiones (Clientes, Productos, Campañas).
- Definición de claves primarias y foráneas para relaciones.
- Uso de **DAX** para métricas calculadas como:
  - Tasa de respuesta por campaña
  - Gasto promedio por categoría
  - Segmentación por generación
- Modelo estrella para optimizar rendimiento y visualizaciones.

### 3. Visualización (Power BI)
- **Página Visión General:** KPIs globales, gasto promedio, tasa de respuesta, compras por canal, gasto por categoría y generación.
- **Página Campañas:** Tasa de aceptación por campaña y generación, impacto en ingresos, análisis comparativo de campañas.
- **Página Comportamiento:** Frecuencia de compra, visitas web, análisis de gasto vs ingreso, patrones por categoría.

---

## 📊 Resultados principales
- **Tasa de respuesta general:** 5.97%.
- **Generación con mayor aceptación:** Generación Silenciosa (8.70%).
- **Canal de compra más utilizado:** Tienda física (38.98%).
- **Categorías de mayor gasto:** Vinos y carne.
- Relación positiva entre ingresos y gasto total (correlación visualmente evidente en gráfico de dispersión).

---

## 📷 Capturas de Dashboard

### Visión General
![Visión General](<img width="1199" height="670" alt="image" src="https://github.com/user-attachments/assets/a3d951c0-841f-4fb6-960d-96f842dc3260" />
)

### Campañas
![Campañas](<img width="1198" height="675" alt="image" src="https://github.com/user-attachments/assets/8662c5b6-9e0b-49bf-a923-350ef473807f" />
)

### Comportamiento
![Comportamiento](<img width="1196" height="675" alt="image" src="https://github.com/user-attachments/assets/034fc8e1-083f-4ab2-8a87-69c328593e6d" />
)

---

## 📌 Conclusiones
- La segmentación por generación y categoría de producto puede guiar estrategias de marketing más efectivas.
- La inversión en canales físicos sigue siendo relevante, pero los clientes con más interacción digital muestran un patrón de respuesta más alto.
- La optimización de campañas requiere integrar análisis de ingresos, historial de compras y engagement digital.

---

## 🚀 Posibles mejoras
- Implementar un modelo predictivo de clasificación (ej. Random Forest o XGBoost) para identificar clientes de alto potencial.
- Incluir datos temporales actualizados para analizar tendencias recientes.
- Incorporar métricas de rentabilidad por campaña.

---

## 📂 Dataset
Dataset original disponible en Kaggle: [Customer Personality Analysis Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

