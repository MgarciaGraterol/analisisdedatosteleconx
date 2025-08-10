# # Análisis de Evasión de Clientes (Churn) - TelecomX

## 📋 Descripción

Este proyecto realiza un análisis de datos para entender y mitigar el problema de evasión de clientes (*Churn*) en la empresa de telecomunicaciones **TelecomX**.  
Se trabaja con un dataset en formato JSON que contiene información demográfica, tipos de servicio contratado, facturación y estado de evasión de los clientes.

---

## 🎯 Objetivo

Identificar patrones y factores asociados con la cancelación del servicio para apoyar estrategias de retención y mejorar la fidelidad de los clientes.

---

## ⚙️ Metodología

1. **Importación y limpieza de datos**  
   - Carga y aplanado de datos JSON anidados.  
   - Tratamiento de valores nulos y duplicados.  
   - Estandarización de categorías y corrección de tipos.  
   - Creación de la columna `Cuentas_Diarias` para análisis más detallado.

2. **Análisis Exploratorio de Datos (EDA)**  
   - Visualización de la distribución de Churn.  
   - Estadísticas descriptivas para variables numéricas.  
   - Comparación de variables clave entre clientes que cancelan y no cancelan.

3. **Visualizaciones**  
   - Gráficos de torta y barras para proporción de clientes.  
   - Boxplots y violinplots para comparar variables numéricas según estado de Churn.

4. **Exportación**  
   - Dataset limpio exportado en formato CSV para futuros análisis y modelado predictivo.

---

## 📊 Resultados Clave

- Clientes con menor tiempo de contrato y menor gasto diario tienen mayor probabilidad de cancelar.
- Servicios adicionales parecen mejorar la retención.
- Contratos a largo plazo muestran mejor fidelización.

---

## 💡 Recomendaciones

- Implementar incentivos para nuevos clientes y contratos largos.  
- Diseñar campañas personalizadas para clientes con bajo gasto.  
- Promover servicios complementarios
