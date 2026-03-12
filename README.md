# 🧪 A/B Test Analysis & Hypothesis Prioritization — E-commerce

## 🎯 Objetivo
Priorización de hipótesis de negocio y análisis completo de test A/B para determinar
qué estrategia incrementa los ingresos de una tienda online.

## 🛠️ Herramientas
Python · Pandas · NumPy · Scipy.stats · Matplotlib · Mann-Whitney U

## 📌 Metodología
- Frameworks ICE y RICE para priorizar 9 hipótesis de negocio
- Eliminación de 58 usuarios duplicados entre grupos (independencia estadística)
- Seguimiento de conversión e ingresos acumulados durante 31 días
- Filtrado de outliers con percentiles 95 y 99 + Mann-Whitney U

## 💡 Resultados
- Diferencia de conversión significativa a favor del Grupo B (p = 0.007)
- Grupo B supera a Grupo A en +18.9% en tasa de conversión (datos filtrados)
- Revenue final Grupo B: $92,840 vs. Grupo A: $64,554

## 🎯 Decisión
Detener la prueba y adoptar la estrategia del Grupo B.
