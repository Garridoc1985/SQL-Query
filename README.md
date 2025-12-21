# 📊 Análisis de Ventas Mensuales y Pronóstico

Este repositorio contiene un ejercicio de analítica desarrollado con el objetivo de demostrar el planteamiento de una **pregunta analítica clara**, el uso coherente de métricas y la **comunicación efectiva de resultados mediante visualizaciones**.

El panel fue construido y publicado en **Tableau Public**, con acceso completamente abierto.

---

## 🧩 Pregunta Analítica

**¿Cómo han evolucionado las ventas mensuales y qué nivel de ventas se puede esperar en los próximos dos años considerando la estacionalidad del negocio?**

---

## 📌 Contexto

El análisis se construyó utilizando un **conjunto de datos de origen propio**, diseñado para representar un escenario realista de ventas mensuales con variabilidad y patrones estacionales.



---

## 📈 Respuesta Analítica

El análisis muestra que las ventas mensuales presentan una alta variabilidad a lo largo del tiempo, sin una tendencia de crecimiento estructural clara, pero con un patrón estacional recurrente. A partir de este comportamiento histórico, se construyó un modelo de pronóstico que replica dicha estacionalidad y proyecta el desempeño esperado para los próximos dos años.

El pronóstico sugiere que las ventas futuras se mantendrían dentro de rangos consistentes con el comportamiento histórico, con fluctuaciones mensuales similares a las observadas previamente. Además, el uso de intervalos de predicción permite visualizar la incertidumbre asociada a estas estimaciones, proporcionando una visión realista tanto del valor esperado como de los posibles escenarios futuros.

---

## 🛠️ Metodología

- **Granularidad:** ventas mensuales  
- **Período histórico:** 2020 – 2024  
- **Horizonte de pronóstico:** 2025 – 2026  
- **Modelo:** ETS (Exponential Smoothing)  
- **Estacionalidad:** aditiva  
- **Intervalo de predicción:** 90 %

---

## 📂 Fuente de Datos

- **Origen:** conjunto de datos de origen propio ( Mackaroo)
- Código de integración/preparación (SQL): definición de tablas + vistas + funciones + stored procedures + triggers (automatizan extracción parametrizada, agregaciones y validaciones).

Modelo entidad relación 
<img width="1157" height="1048" alt="image" src="https://github.com/user-attachments/assets/4047b14e-a588-442a-b284-3827948d5faa" />

Diagrama entidad relacion EER 

<img width="921" height="1190" alt="image" src="https://github.com/user-attachments/assets/d6cf0575-62e0-4115-b53a-db54705e77d6" />


- Limpieza: auditoría de cambios/borrados para control de calidad y trazabilidad.
- **Uso:** fines analíticos y demostrativos  

---

## 🔗 Dashboard Público

👉 *(https://public.tableau.com/views/DesafioPanel/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)*

---

## 📎 Herramientas Utilizadas

- Tableau Public  
- CSV (datos de entrada)  
---

## ℹ️ Notas

Este proyecto fue desarrollado como parte de un desafío de analítica con el objetivo de evaluar el razonamiento analítico, la estructuración del análisis y la comunicación de insights a partir de datos.
