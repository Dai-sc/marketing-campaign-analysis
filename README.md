![Status del Proyecto](https://img.shields.io/badge/Status-Completado-green.svg)

# Optimización de Campañas de Email Marketing

---

### Introducción al Proyecto

La empresa de e-commerce "Aura Glow" ha experimentado una disminución en la efectividad de sus campañas de email marketing durante los últimos seis meses. Se sospecha que el problema radica en una estrategia genérica de envío que no considera el comportamiento ni las preferencias de su audiencia. Esto ha generado una caída en métricas clave como la Tasa de Conversión y la Tasa de Clics (CTR).

Este proyecto de análisis de datos tiene como objetivo identificar los puntos débiles de la estrategia actual, analizar el rendimiento de las campañas y proponer mejoras concretas basadas en datos para incrementar el engagement y el retorno de inversión (ROI) de la empresa.

---

### Análisis y Hallazgos Clave

El análisis exploratorio de datos (EDA) reveló `insights` cruciales sobre la audiencia y la estrategia de la empresa:

* **Correlación entre métricas**: Se encontró una fuerte correlación positiva entre el **CTR** y la **Tasa de Conversión**. Esto significa que a mayor interacción (más clics), mayor es la probabilidad de que se genere una venta, lo que convierte al CTR en una métrica principal para la optimización.
* **Comportamiento por día de la semana**: Existe una aparente discrepancia, que en realidad es un hallazgo valioso. El **lunes** se identificó como el mejor día para **conversiones** (ventas), mientras que el **jueves** es el día ideal para el **`engagement`** (clics). Este patrón demuestra un comportamiento de usuario diferenciado a lo largo de la semana que puede ser explotado.
* **Segmentación de la audiencia**: El análisis inicial mostró que los segmentos de clientes predefinidos (como 'Tech Enthusiasts' o 'Foodies') tienen un rendimiento muy similar, lo que refuerza la idea de que se utiliza una estrategia de "talla única". Para abordar esto, se crearon segmentos lógicos basados en el comportamiento real de los usuarios, revelando tres grupos clave: **Audiencia `Engaged`**, **Audiencia Receptiva** y **Audiencia Inactiva**, cada uno con un rendimiento y potencial distintos.

---

### Recomendaciones Estratégicas

Basado en los hallazgos del análisis, se proponen las siguientes recomendaciones para optimizar las campañas de email de la empresa "Aura Glow":

1.  **Implementar una Estrategia de Envío Multiobjetivo**: Reconociendo que el lunes es el mejor día para las conversiones y el jueves para el `engagement`, se recomienda diversificar los envíos según el objetivo de la campaña.
2.  **Optimizar el `Engagement` General**: La fuerte correlación entre CTR y conversión subraya que aumentar los clics es la principal palanca para impulsar las ventas. La empresa debe mejorar elementos como líneas de asunto, diseños y llamadas a la acción (CTA) para toda su base de datos.
3.  **Personalizar el Contenido por Segmento**: Pasar de un enfoque genérico a uno personalizado, creando campañas de email específicas que se alineen con los intereses de cada segmento (ej., ofertas relevantes para 'Health & Wellness' o contenido para 'Foodies').
4.  **Desarrollar Estrategias Específicas para Cada Segmento por Comportamiento**: Implementar campañas especializadas para los nuevos segmentos creados:
    * **Audiencia `Engaged`**: Recompensarlos con campañas exclusivas y promociones especiales para maximizar las conversiones.
    * **Audiencia Receptiva**: Nutrir este segmento con contenido educativo o testimonios para superar las barreras a la conversión.
    * **Audiencia Inactiva**: Intentar reactivarlos con campañas de re-engagement y, si es necesario, removerlos de la base de datos.

---

### Tecnologías Utilizadas

El proyecto fue desarrollado utilizando Python y las siguientes librerías principales:

* `Pandas`: Para la manipulación y análisis de datos.
* `NumPy`: Para operaciones numéricas.
* `Matplotlib` y `Seaborn`: Para la visualización y exploración de datos.
* `Scikit-learn` (`Sklearn`): Para técnicas de preprocesamiento de datos (`MinMaxScaler`).

---

### Fuente de Datos

El conjunto de datos utilizado para este proyecto fue obtenido de **Kaggle**.

---

### Estructura del Repositorio

El repositorio se estructura en dos `notebooks` de Jupyter, que reflejan el flujo de trabajo del proyecto:

* `ETL.ipynb`: Contiene el código para la **Extracción, Transformación y Carga** de los datos.
* `EDA.ipynb`: Contiene el **Análisis Exploratorio de Datos** y las conclusiones finales.
