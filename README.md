# Pre_Entrega_Machine_learning

## Pre-Entrega — Proyecto de Machine Learning

### Análisis de factores ambientales y químicos que influyen en la velocidad de corrosión en aceros inoxidables

---

## Descripción del proyecto

El presente trabajo corresponde a la pre-entrega del proyecto final de Machine Learning, enfocado en el análisis y procesamiento de datos relacionados con fenómenos de corrosión en aceros inoxidables.

El objetivo principal consiste en estudiar cómo distintos factores ambientales y químicos influyen en la velocidad de corrosión de materiales metálicos, utilizando técnicas de análisis exploratorio de datos (EDA), limpieza y transformación de datos orientadas a futuras etapas de modelado predictivo.

---

## Dataset utilizado

El proyecto utiliza el dataset **CORR-DATA**, correspondiente a información experimental sobre corrosión en materiales metálicos expuestos a distintos entornos químicos y ambientales.

El archivo CSV utilizado en el análisis se encuentra incluido dentro de este repositorio:

[Descargar dataset CORR-DATA](./CORR-DATA_Database.csv)

---

## Objetivo del análisis

El proyecto busca:

- Analizar variables relacionadas con corrosión en aceros inoxidables.
- Identificar relaciones entre temperatura, entorno químico, concentración y velocidad de corrosión.
- Detectar patrones relevantes mediante análisis exploratorio de datos.
- Preparar el dataset para futuras etapas de Machine Learning.

---

## Variables seleccionadas

Las variables utilizadas para el análisis fueron:

- `Environment`
- `Material Group`
- `Material Family`
- `Material`
- `Rate (mm/yr) or Rating`
- `Localized Attack`
- `Condition/Comment`
- `Concentration (Vol %)`
- `Temperature (deg C)`
- `Duration`

Las demás columnas fueron descartadas debido a que contienen identificadores, referencias bibliográficas o códigos internos con bajo valor analítico para los objetivos del proyecto.

---

## Tecnologías y librerías utilizadas

El análisis fue desarrollado en Python utilizando principalmente las siguientes librerías:

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## Etapas desarrolladas

### 1. Selección del dataset
- Identificación del problema.
- Justificación de elección.
- Selección de variables relevantes.

### 2. Análisis Exploratorio de Datos (EDA)
- Inspección inicial del dataset.
- Estadísticas descriptivas.
- Análisis de valores faltantes.
- Distribución de variables.
- Visualizaciones gráficas.
- Matriz de correlación.

### 3. Limpieza y transformación de datos
- Tratamiento de valores nulos.
- Conversión de tipos de datos.
- Filtrado de registros.
- Preparación de variables categóricas y numéricas.

### 4. División del dataset
- Separación en conjuntos de entrenamiento y prueba para futuras etapas de modelado.

## Tamaño del dataset

Luego de la selección inicial de variables, el dataset contiene:

- **24.721 registros**
- **10 variables**


