# EVA2-Preprocesamiento-de-datos-

# Análisis de Campañas Bancarias - Preprocesamiento y Visualización (EVA2)

Este proyecto realiza un análisis exhaustivo y preprocesamiento de datos del dataset **"bank-additional-full.csv"**. El objetivo es transformar datos brutos en información estratégica para el Banco Financiero Global, asegurando que el conjunto de datos sea apto para futuros modelos predictivos de Machine Learning.

## 📂 Estructura del Proyecto

El repositorio sigue una estructura modular para facilitar la mantenibilidad y escalabilidad del código:

```text
.
├── data             # Contiene los archivos CSV (Raw y Clean)
├── notebooks        # Informes técnicos en formato Jupyter (.ipynb)
├── src              # Scripts de Python con la lógica del negocio
│   ├── cleaner.py   # Clase para limpieza y preprocesamiento
│   └── visualizer.py # Clase para generación de gráficos profesionales
├── outputs          # Gráficos exportados y reportes finales
└── README.md        # Documentación principal
🛠️ Tecnologías Utilizadas
Lenguaje: Python 3.x

Librerías de Datos: Pandas, NumPy

Visualización: Matplotlib, Seaborn

Entorno: Visual Studio Code / Jupyter Notebooks

⚙️ Proceso de Preprocesamiento
Siguiendo los requerimientos técnicos del caso, se aplicaron las siguientes transformaciones mediante Programación Orientada a Objetos (POO):

Traducción Técnica: Los atributos y valores fueron traducidos al español para alinearse con los requerimientos del negocio.

Gestión de Nulos: Conversión de valores "desconocido" a nulos reales (NA) e imputación mediante la moda de cada categoría.

Tratamiento de Outliers: Aplicación de técnica de Capping en variables numéricas para evitar sesgos por valores extremos.

Ingeniería Ética: Eliminación de la variable duracion, ya que su inclusión en modelos predictivos no es ética ni realista para el escenario propuesto.

Estandarización: Eliminación de registros duplicados para asegurar la integridad del análisis.

📊 Visualización de Datos
Se generaron 15 gráficos estratégicos utilizando Matplotlib y Seaborn para identificar tendencias clave:

Perfil del Cliente: Distribución de edad, trabajo y nivel educativo.

Estrategia de Campaña: Impacto del canal de contacto y estacionalidad mensual.

Contexto Económico: Relación con la tasa Euribor e índices de confianza del consumidor.

Análisis de Correlación: Matriz de calor para identificar dependencias entre variables numéricas.

🚀 Instalación y Uso
Clonar el repositorio.

Asegurarse de tener instalado Python y las dependencias necesarias (pandas, matplotlib, seaborn).

Ejecutar el notebook notebooks/informe_tecnico_final.ipynb para visualizar el análisis completo.

Curso: Preprocesamiento de Datos (ADY1100)

Institución: Duoc UC

Evaluación: Parcial N°2 - Entrega de Encargo


### Instrucciones adicionales:
1. **Archivo `cleaner.py`**: Asegúrate de que el código que tienes en `src/cleaner.py` sea la versión estable (sin el escalamiento que daba error de memoria) para que cualquiera que clone tu repo pueda correrlo de inmediato.
2. **Archivo `visualizer.py`**: Verifica que los nombres de las columnas coincidan con el archivo traducido.
3. **GitHub**: Al subirlo, este `README` se verá automáticamente en la página principal de tu proyecto, dándole una apariencia de ingeniería civil en informática de alto nivel.
