![Status del Proyecto](https://img.shields.io/badge/Status-Completado-green.svg)

# 📈 Optimización de campañas de email marketing

---

### 🌟 Introducción al proyecto

La empresa de e-commerce "Aura Glow" ha notado una caída en la efectividad de sus campañas de email. A pesar de los envíos constantes, la tasa de conversión y el `engagement` han disminuido.

Este proyecto tiene como objetivo analizar a fondo los datos de las campañas para descubrir por qué están fallando y proponer una estrategia basada en datos para impulsar el `engagement` y el retorno de inversión (ROI).

---

### 🔍 Hallazgos clave

El análisis exploratorio de datos (EDA) reveló `insights` cruciales para entender el comportamiento de la audiencia:

* **La clave está en los clics:** Se encontró una **fuerte correlación positiva entre el CTR y la Tasa de Conversión**. Esto confirma que a mayor interacción (más clics), mayor es la probabilidad de generar ventas.
* **Cada día tiene su propósito:** El **lunes** es el mejor día para las **ventas**, mientras que el **jueves** es ideal para conseguir **clics**. Este patrón demuestra que el comportamiento del usuario cambia según el día.
* **Una audiencia con potencial:** Al crear nuevos segmentos, descubrimos que los clientes se dividen en tres grupos según su comportamiento:
    * **Audiencia `Engaged`**: Muy activos y listos para comprar.
    * **Audiencia Receptiva**: Hacen clic, pero rara vez convierten, un gran potencial sin explotar.
    * **Audiencia Inactiva**: No interactúan con los correos.

---

### 🚀 Recomendaciones estratégicas

Basado en el análisis, se proponen las siguientes acciones para optimizar las campañas de email de "Aura Glow":

1.  **Estrategia de Envío Inteligente:** Enviar correos de venta los **lunes** y correos con contenido para generar `engagement` los **jueves**.
2.  **Mejorar los Correos:** Optimizar elementos como líneas de asunto y CTA para aumentar los clics y, por ende, las ventas.
3.  **Personalizar Contenido:** Adaptar el contenido de los correos según los intereses de cada segmento ('Tech Enthusiasts', 'Foodies', etc.).
4.  **Atacar a cada Segmento por su Comportamiento:**
    * **`Engaged`**: Ofrecer promociones y accesos exclusivos.
    * **Receptivos**: Enviar reseñas de productos y testimonios para animarlos a comprar.
    * **Inactivos**: Lanzar campañas de reactivación o eliminarlos de la base de datos para mejorar las métricas.

---

### 🛠️ Tecnologías y herramientas

* **Lenguaje**: Python
* **Librerías**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn` (`Sklearn`)
* **Fuente de Datos**: Kaggle

---

### 📂 Estructura del repositorio

El proyecto se organiza en dos carpetas principales para mantener el flujo de trabajo ordenado y reproducible:

* `data/`: Contiene el conjunto de datos limpio y procesado (`marketing_campaign_email_clean.csv`).
* `notebooks/`: Almacena los `notebooks` de Jupyter (`ETL.ipynb` y `EDA.ipynb`) que contienen el código de análisis.
