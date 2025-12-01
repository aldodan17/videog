🎮 Análisis de Ventas y Tendencias en la Industria de Videojuegos

Identificación de patrones de éxito, segmentación por plataforma y género, análisis regional y pruebas estadísticas.

🧠 Descripción general del proyecto

Este proyecto analiza datos históricos de ventas de videojuegos para identificar los factores que determinan si un título tiene éxito. Se estudian plataformas, géneros, reseñas de usuarios y críticos, así como comportamientos de mercado por región (NA, EU, JP). El objetivo es detectar tendencias y estimar qué juegos serían prometedores para campañas de marketing en 2017.

Incluye limpieza profunda del dataset, análisis exploratorio, visualizaciones avanzadas, correlaciones, construcción de perfiles por región y pruebas de hipótesis.

🛠️ Tecnologías utilizadas

Python

pandas (limpieza y transformación de datos)

numpy (estadística y cálculos)

matplotlib / seaborn (visualizaciones)

scipy.stats (pruebas de hipótesis)

Jupyter Notebook

📌 Metodología del proyecto
1️⃣ Preparación y limpieza del dataset

Normalización de nombres de columnas.

Conversión de tipos (fecha, numéricos).

Tratamiento de valores ausentes (incluyendo manejo de TBD).

Creación de la variable total_sales sumando todas las regiones.

Exploración de outliers y datos inconsistentes.

2️⃣ Análisis exploratorio (EDA)

Conteo de juegos lanzados por año.

Evolución de ventas por plataforma para identificar ciclos de vida.

Selección del periodo relevante para modelar ventas de 2017.

Detección de plataformas líderes, en crecimiento y en declive.

Diagramas de caja para comparar ventas globales entre plataformas.

3️⃣ Impacto de reseñas en ventas

Gráficos de dispersión entre reseñas vs. ventas.

Correlación entre críticas, usuarios y ventas globales.

Comparación entre plataformas populares (PS4, XOne, PC).

4️⃣ Perfil de usuario por región

Para NA, EU y JP se determinaron:

Top 5 plataformas.

Top 5 géneros.

Influencia del rating ESRB en ventas regionales.

Comparativas de preferencias culturales.

5️⃣ Pruebas de hipótesis

Se evaluaron:

H₀: Las calificaciones de usuarios para Xbox One y PC son iguales.

H₀: Las calificaciones de Acción y Deportes no difieren.

Incluye:

Formulación de H₀ y H₁.

Selección del test adecuado (t-test o Mann-Whitney).

Definición de α.

Interpretación del p-value y toma de decisiones.

📈 Resultados principales

Identificación de plataformas dominantes y en declive.

Hallazgo de géneros más rentables y sus variaciones regionales.

Correlación positiva entre reseñas profesionales y ventas en ciertas plataformas.

Diferencias culturales marcadas entre NA/EU/JP.

Validación o rechazo de hipótesis mediante métodos estadísticos.

🧪 Conclusión

Este proyecto demuestra dominio en:
✔ Limpieza profesional de datos
✔ EDA orientado a negocio
✔ Análisis de mercado y comportamiento del usuario
✔ Visualización clara de métricas
✔ Pruebas estadísticas para toma de decisiones
✔ Documentación completa en Jupyter
